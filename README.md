# Münsterplatine – a pcb for LoRaWan

(Münsterplatine ist german for minster pcb.)

Welcome to the TTN Ulm Münsterplatine repository.
Our local TTN-community was under the impression that there is a tremendous need for a cheap and easy to use LoRaWan All-in-one kit, and so we created one.
The work is build around the ready-made arduino Pro Mini which can be bought from various sources for under 3 EUR per piece and the RFM96W LoRa tranceiver for communication. 

# 2nd version

(Most recent revision is v1.1)

In this version we added a multitude of goodies for you comfort as a LoRaWan-enthusiast. 
The features include:
* onboard FTDI and USB, so you can flash your Arduino easily by connecting it to your PC directly
* battery connector
* _battery charger_ included, so you can charge your LiPo-battery while plugged into the PC
* a combinded wire/ufl/sma connector is also onboard.
	
# 1st version

This version aimed to satisfy you basic LoRaWan needs in form of a pcb on which the Arduino Pro Mini and the RMF95W-module can be soldered together. 
But beware: You still need a FTDI USB<->Serial converter to flash your Arduino. 
Since there is no additional hardware, this version is less energy-hungry than Version 2

You can find this version in the [legacy branch](https://github.com/verschwoerhaus/ttn-ulm-pcb/tree/legacy).
