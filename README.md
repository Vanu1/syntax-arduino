# SYNTAX-ARDUINO
Arduino is a great open-source electronics prototyping platform based on flexible easy-to-use hardware and software. It is basically a simplified microcontroller, in the sense that it uses a normal microcontroller and envelopes its internal functioning which may impede its functioning, but it gives us a very handy, easy to use tool.
It is basic version of **C**



Arduino programming language can be divided in three main parts:
* Function
* Variable and Constant
* Structure


##### Image of arduino UNO


![image uno arduino board](https://cdn.pixabay.com/photo/2017/03/23/12/32/arduino-2168193_960_720.png)


##### Image of arduino nano


![nano board](https://www.behind-the-scenes.co.za/wp-content/uploads/arduino-nano-v3-basic-pinout.jpg)


## Structure:
* #### sketch:
  * **setup()**:-The `setup()` function is used to initialize variables,pin modes,start using libraries etc. the setup function runs only once in a program.
  ```
  void setup(){
  
  }
  ```
  * **loop()**:-After creating `setup()` function,the loop functions run program consecutively and allow our program to change and respond
  ```
  void loop(){
  
  }
  ```

* #### Arithmetic Operator:
  * **+** (addition)
  *  \* (multiplication)
  * **-** (substraction)
  * **/** (division)
  * **%** (remainder)
  * **=** (assignment operator)
* #### Comparison Operator:
  * **!=** (not equals to)
  * **==** (equals to)
  * **>** or **>=** (less than or less than equals to)
  * **<** or **<=** (greater than or greater than equals to)
* #### Control Structures :
  * **break**:-use to exit from loop (`for`,`while`,`do....while`).
  * **continue**:-It skip the current iteration of loop (`for`,`while`,`do....while`).
  * **if and else statements**:-use as conditionals.example
  ```
  if(condition 1){
  // your code here
  }
  if else(condition 2){
  // your code here  executes if condition 1 is false and condition 2 is true
  }
  else{
  //your code here executes if condition 1 & 2 is false.
  }
  ```
  * **return**:-Terminates a functions and return value from it if it is called.`return ;`.
  
  
## Function:
* #### Digital I/O:
  * **PinMode()**:-It specifies pin to behave either as `INPUT` or `OUTPUT`.It is possible to enable the internal pullup resistors with the mode `INPUT_PULLUP`.
  
  ```
  pinMode(pin,mode);
  ```
  * **DigitalRead()**:-It reads the pin either as `HIGH` or `LOW`.
  
  ```
  digitalRead(pin);
  ```
  * **DigitalWrite()**:-Assign value either as `HIGH` or `LOW`.
  ```
  digitalWrite(pin,value);
  ```
 * #### Analog I/O:
   * **AnalogRead()**:-Read value from specified analog pin and Arduino boards contain 10-bit analog to digital converter. This means that it  will map input voltages between 0 and the 5 into integer values between 0 and 1023 and returns it.
   ```
   analogRead(pin);  
   ```
   * **AnalogWrite()**:-Assign value b/w 0 to 255 (*duty cycle*) to analog pin.
   ```
   analogWrite(pin,value);
   ```
   * **AnalogReference()**:-Configures the reference voltage used for analog input (the value used as the top of the input range).Type of reference to use is according to board and need. Use [link](https://www.arduino.cc/reference/en/language/functions/analog-io/analogreference/) here to get reference type.
   ```
   analogReference(type);
   ```
 * #### Other Important Functions:
   * **delay()**:-Pauses the program for the amount of time(*ms*).
	 ```
	 delay(time);
	 ```
   * **millis()**:-It returns the time paased since arduino began running the current program.
	 ```
	 time=millis();
	 ```
## Variables & Constants :
* #### Data types:
  * **char**:-stores characters 
  * **float**:-stores floating point values 
  * **int**:-stores intergers
  * **string**:-stores string `" "`
  
* #### Constants:
  * **HIGH**
  * **LOW**
  * **INPUT**
  * **OUTPUT**
  * **INPUT_PULLUP**
  * **true**
  * **false**

#### *Basic code of led blinking*

![](https://raw.githubusercontent.com/Vanu1/syntax-arduino/master/2020-04-13.png)

  
  
**for any doubts in above article  please refer [click here](https://www.arduino.cc/reference/en/)** 
  
  
  
  
   
   
