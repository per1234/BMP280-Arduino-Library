BMP280 Arduino Library
======================
Pin Connection : 

BMP280-----Arduino

VDD   ----> 3.3V
GND   ----> GND
SDA   ----> PIN20 (arduino mega) 
SCL   ----> PIN21 (arduino mega)
SDO   ----> GND   (slave address 0x76)
CS    ----> VDD   (HIGH for I2C)
VDDIO ----> VDD


Instructions : 
Copy the BMP280 folder to Arduino/libraries

Restart Arduino and Upload "measurments" sketch in Arduino.




