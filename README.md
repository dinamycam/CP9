# CP9
car projects:
these are the porjects me and my friend
[@hadiyadollahi]()
are collecting
so that we can do some of them, in our free time, and see what comes out of them. <br>
however , things listed here are just basic ideas that will become better documented over time...


## 1. **autoConnect**
while somehow inspired by flexihub,
the basic idea is to have a music player,**but** way cooler!<br>
you can connect usb drives wirelessly to it!
this way, the number of simultaneously connected devices can increase significantly, limited to the wifi chip design; <br>
it can become even better, if you can control the player wirelessly, as well.

awesome , isn't it? :smile:


### tools needed:
* [ 2 * esp8266 chips ](https://nurdspace.nl/ESP8266)
   - one for acting as an Access Point
   - one for being the station
* a USB flash drive

### details:
the esp8266 chip is one of the most awesome chips I've ever discovered
i've found some tutorials related to using it.some firmwares, like a upython port, and an elua firmware! the possibilities are limitless!
##### ***testing and results:***
* currently none ;)

#### links:
* [hackaday](http://hackaday.com/2015/03/18/how-to-directly-program-an-inexpensive-esp8266-wifi-module)
* [nurdspace]( https://nurdspace.nl/ESP8266 )

## 2. **adjust the interior temperature of the car**
the LM35 is an integrated circuit sensor that can be used to measure temperature with an electrical output proportional to the temperature (in OC).


### components needed to build the LM35 temperature sensor circuit:
* arduino board
* LM35 temperature sensor IC
* usb with type A&B connectors


### details:
LM35 temperature sensor can be measured.
we will integrate this with the arduino to measure the temperature.
the arduino will then read this measure value from the LM35 & translate into degrees fahrenheit and celsius, 
which we will be able to read from the computer from the arduino serial monitor.
