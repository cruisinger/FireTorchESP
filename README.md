# FireTorchESP
LED effects including an impressive firetorch effect with an ESP8266 and WS2812B

This project combines  
https://www.tweaking4all.com/hardware/arduino/arduino-all-ledstrip-effects-in-one/
and 
mrks's wonderful arduino driven "Fackelmob"
http://mrks.de/project/Elektrischer_Fackelmob/22, 
adapted for using with the ESP8266

I intend to make the different light routines changeable throuth mqtt messages. 
In this early version it works, but it hangs in some routines and there is no way to change to another program.

You only need an ESP8266 based mcu, like an NodeMCU, Wemos, ESP12F, an WS2812B LED Stip, (perhaps a levelshifter for getting an better signal)
