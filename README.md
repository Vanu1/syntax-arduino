# syntax-arduino
*Arduino is a great open-source electronics prototyping platform based on flexible easy-to-use hardware and software. It is basically a simplified microcontroller, in the sense that it uses a normal microcontroller and envelopes its internal functioning which may impede its functioning, but it gives us a very handy, easy to use tool.It is very similar to your **ESC101***

this language can be divide into 3 main parts:

* **functions**

* **variable and constants**

* **structure**

![](https://raw.githubusercontent.com/Vanu1/syntax-arduino/master/arduino.jpg)

## Functions
#### Digital I/O:
* **pinMode()**-Configures the pin to behave as **INPUT** OR **OUTPUT**. This function return nothing.
Here pin digital pins on the arduino boards.**syntax**:
```
pinMode(pin,mode)
```
* **digitalRead()** - Reads the value from a specified digital pins either **HIGH** OR **LOW**.
Here pin is the digital pin whose value you want to read ranging from 0 to 13 and returns either HIGH OR LOW.**syntax**:
```
digitalRead(pin)
```
* **digitalWrite()** -It basically assign **HIGH** or **LOW** value to digtal pins. In digital HIGH means 5 volts and LOW means 0 volts.**syntax**:
```
digitalWrite(pin,value)
```
#### Analog I/O:
* **analogRead()**-Read value from specified analog pin similar to digitalRead() but it maps input voltage b/w 0 volt and 5 volts
into integers 0 to 1023.Actually arduino use 10 bit analog to digital conveter.**syntax**:
```
analogRead(pin)
```
* **analogReference()**-Configures the reference voltage used for analog input (i.e. the value used as the top of the input range).
here type varies from board to board.Use this link to chose type according to your board [reference](https://www.arduino.cc/reference/en/language/functions/analog-io/analogreference/)**syntax**:
```
analogReference(type)
```
* **analogWrite**-writes an analog value to pin,used to light led at diffrent brightness.it returns nothing.Value in code block is duty cycle b/w 0(always off) and 255(always on).allowed data type is `int` .**syntax**:
```
analogWrite(pin,value)
```
#### Other Important Functions:
* **delay()**-It pause the program for time specified as a parameter in *ms*,returns nothing and **syntax**:
```
delay(ms)
```
* **millis()**-It simply returns the no. of millisecond passed since the arduino board running the current program.Here time is a variable storing that time in *ms*. **syntax**:
```
time=millis()
```
## Variable
