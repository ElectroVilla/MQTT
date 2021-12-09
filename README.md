# MQTT
How to build a complete MQTT solution (ESP8266 + Alexa + Android)

<< This repository is made specially to honor the best man on the internet who teaches Android, Philipp Lackner, https://www.youtube.com/c/PhilippLackner who make the best YouTube videos and professional courses >>

The focus of this repo is to conclude how to simple smart home system by building the basic items simple steps, thanks to the original authors that made life easy, I just collected the data and made a few modifications to the Android code.


Step 1:

a) Setup IDE environment for ESP8266 on VS code 

b) Do MQTT Account and topic

c) Go through the steps to build Alexa skill so it can control your ESP8266 over the internet by voice commands  

All described in that link for its respected author: https://www.youtube.com/watch?v=LI3x1jG0nCY 


Step 2: 

In order to be able to access your ESP8266 from your android phone, you need to write the code of this repository   

a) The original code comes from this account: https://github.com/yazdipour/MQTT-Kotlin-Sample

b) Minor modification was made to change the MQTT broket to the one in step 1

c) The code as it is will not work, you have to put your MQTT credentials first then it'll work 


Step 3:

Is to make the total solutions dynamic:

a) Accept different user account (from different customers)

b) Increase the hardware capabilities beyond what the ESP8266 has.

c) Build iOS application

d) Build system configurations tool

e) many other features that make the smart home brands so special
