# simple-rest-pixel-controller

ESP8266 sketch to allow WS281x lights to be controlled via a simple rest api(at least at first)

## Goal

Is to make it so I can enable my light display to be controlled by perhaps an SMS interface.  So likely would have a raspberry pi for that interface portion which in turn would call the rest api on the ESP.

## Why do this this?

Many folks have static displays, and there isn't anything wrong with that.  I want an interactive display, something the "audience" can interact with.  So keep the light controller kind of dumb is probably going to be goal.  But I thought I would share this little bit of code because maybe others would like to see how something really simple like it works.

## What do you need?

From a hardware perspective I used a NodeMCE ESP8266 and some WS2811 string lights.  From the software, I used the ESP8266 libraries, Restfully, and Adafruit_NeoPixel, ArduinoJson, and maybe I'll add MQTT at some point as well(I like the idea of that a little better long term).

The only things that need configured; light count, pin number, type of lights, hostname, ssid, and password for said ssid.

Anything else, is mostly up to you.  This is my first foray into Arduino, and so maybe as time progresses, some silly ways of doing things will get better(or maybe not) we shall see.


