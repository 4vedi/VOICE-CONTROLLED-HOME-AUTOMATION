# VOICE-CONTROLLED-AUTOMATION!

Home automation is part of "The Internet of Things," also known as IoT. The way devices and appliances can be networked together to provide us with seamless control over all aspects of your home and more.

# PARTS REQUIRED:

1. NodeMCU (you can use any other board which gives wifi functionality like wemos
2. Android Phone (To control the appliances via voice)
3. Blynk App
4. IFTTT
5. 5v Relay (I have 2 channel relay - You can use any number of relay upto which your board can give output)
6. 3.3v - 5v Breadboard powersupply 
7. 12v powersupply (Any 12v prefered more than 1A like LED Strip Driver)
8. Connecting wires, jumper wires, screw drivers.
9. LEDS, BULBS(whatever electrical appliances you may prefer)
10. Arduino IDE

# Flashing ESP8266 with blynk code:


Prepare your Arduino IDE according to ESP8266 boards, detailed installation instructions - "http://esp8266.github.io/Arduino/versions/2.0.0/doc/installing.html"

Flash "https://github.com/4vedi/VOICE-CONTROLLED-HOME-AUTOMATION/Arduino-ESP8266.ino" by editing out authentication code, Wifi SSID, password and then uploading the code 

Detailed Blynk Tutorials - "https://www.youtube.com/channel/UCKWBP3MdpMQFdOCQ63mhC_Q"

Here you can check how to set up an IFTTT account -  "https://ifttt.com"


 # Configuring Blynk and IFTTT
 
 After setting up your Blynk account create a new button. You can directly turn on or off with this button(your appliance should be connected to d1 port . Note: d1 differs for Arduino Uno and Nodemcu so it needs to be converted as we are working on Nodemcu.) 
 
 ![alt](https://github.com/4vedi/VOICE-CONTROLLED-HOME-AUTOMATION/blob/master/Screenshot_2019-03-13-23-54-21-841_cc.blynk.png?raw=true)
 
 
 
 
 
 
 IFTTT Configuration:
 
 Download and install IFTTT app on your android device.
 Set up your IFTTT account
 Create a new applet
 select "OK GOOGLE" as your trigger
 complete the phrase parts according to your needs.
 Select "WEBHOOKS" as your action service.
 Make a web request and fill the form like the screenshot beow.
 (Note: you will get an individual Auth key after you had created a button on BLynk app. It would be send to the account with which you had signed up on BLynk for eg: gmail.com)
 (Note: For URL, enter as follows : http://188.166.20.43/yourauthkey/update/d1(your_arduino_pin)
 
 ![alt](https://github.com/4vedi/VOICE-CONTROLLED-HOME-AUTOMATION/blob/master/IMG_20160525_160913-2.jpg?raw=true)
 


# Preparing Your Circuit

Keep everyting handy and follow the schematic diagram as shown below

You can edit out output pins in blynk as we are virtually writing data on blynk

Schematic is as follow 

![alt](https://github.com/4vedi/VOICE-CONTROLLED-HOME-AUTOMATION/blob/master/Schematic.JPG?raw=true)

# CONCLUSION:


This is very DIY project and can help in controlling your home even when you are far away from home You can add as many connections as much your controller allows! If you want to control only in local wifi, then I also have web server code lemme know I will upload that also




  












