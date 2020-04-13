# syntax-arduino
*Arduino is a great open-source electronics prototyping platform based on flexible easy-to-use hardware and software. It is basically a simplified microcontroller, in the sense that it uses a normal microcontroller and envelopes its internal functioning which may impede its functioning, but it gives us a very handy, easy to use tool.
It syntax is simply **ESC101***
Arduino programming language can be divided in three main parts:
* Function
* Variable and Constant
* Structure

![image os arduino board](https://www.arduino.cc/en/uploads/Tutorial/inputPullupSerial_sch.png)
### Function:
* #### Digital I/O:
  * **PinMode()**:-It specifies pin to behave either as `INPUT` or `OUTPUT`.It is possible to enable the internal pullup resistors with the mode `INPUT_PULLUP`.
  **syntax**
  ```
  pinMode(pin,mode)
  ```
  * **DigitalRead()**:-It reads the pin either as `HIGH` or `LOW`.
  **syntax**
  ```
  digitalRead(pin)
  ```
  * **DigitalWrite()**:-Assign value either as `HIGH` or `LOW`.**syntax**
  ```
  digitalWrite(pin,value)
  ```
 * #### Analog I/O:
   * **AnalogRead()**:-Read value from specified analog pin and Arduino boards contain 10-bit analog to digital converter. This means that it  will map input voltages between 0 and the 5 into integer values between 0 and 1023 and returns it.**syntax**
   ```
   analogRead(pin)
   ```
   * **AnalogWrite()**:-Assign value b/w 0 to 255 (*duty cycle*) to analog pin.**syntax**
   ```
   analogWrite(pin,value)
   ```
   * **AnalogReference()**:-Configures the reference voltage used for analog input (the value used as the top of the input range).Type of reference to use is according to board and need use [link](https://www.arduino.cc/reference/en/language/functions/analog-io/analogreference/) here to get reference type.**syntax**
   ```
   analogReference(type)
   ```
 * #### Other Important Functions:
   * **delay()**:-Pauses the program for the amount of time(*ms*).**syntax**
	 ```
	 delay(time)
	 ```
	 * **millis()**:-It returns the time paased since arduino began running the current program.**syntax**
	 ```
	 time=millis()
	 ```
### Variables:
* #### Data types:
  * **char**:-stores characters 
  * **float**:-stores floating point values 
  * **int**:-stores intergers
  * **string**:-stores string `" "`
  * **array**:-stores array
* #### Constants:
  * **HIGH|LOW**
  * **INPUT|OUTPUT|INPUT_PULLUP**
  * **true|false**
### Structure:
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
##### *Basic code of led blinking*
  
  
   
   
