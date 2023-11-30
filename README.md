# Voice-controlled-home-automation-system-using-Arduino.
A voice-controlled home automation system using Arduino is a system that allows you to control your home appliances using your voice. This can be done using a variety of methods, such as using a voice recognition app or using a Bluetooth module.

Components Required:

Arduino Uno
HC-05 Bluetooth Module
Relay Module
Jumper Wires
Breadboard
Android Phone
Microphone

Steps:
Connect the HC-05 Bluetooth Module to the Arduino Uno:
Connect the VCC pin of the HC-05 to the 5V pin of the Arduino Uno.
Connect the GND pin of the HC-05 to the GND pin of the Arduino Uno.
Connect the RX pin of the HC-05 to the pin 10 of the Arduino Uno.
Connect the TX pin of the HC-05 to the pin 11 of the Arduino Uno.

Connect the Relay Module to the Arduino Uno:
Connect the VCC pin of the Relay Module to the 5V pin of the Arduino Uno.
Connect the GND pin of the Relay Module to the GND pin of the Arduino Uno.
Connect the IN1 pin of the Relay Module to the pin 12 of the Arduino Uno.

Install the Voice Recognition App:
There are many different voice recognition apps available for Android phones. You can choose any one that you like.
Once you have installed the app, open it and follow the instructions to set it up.

Pair the HC-05 Bluetooth Module with Your Android Phone:
Open the Bluetooth settings on your Android phone.
Search for the HC-05 Bluetooth module and tap on it.
Enter the pairing code for the HC-05 Bluetooth module. The default pairing code is 1234.

Upload the Arduino Code:
Connect the Arduino Uno to your computer using a USB cable.
Open the Arduino IDE and select the Arduino Uno from the board list.
Copy and paste the Arduino code into the IDE.
Click on the upload button to upload the code to the Arduino Uno.

Test the System:
Open the voice recognition app on your Android phone.
Say the command "Bulb on", "Bulb off" or "Fan on", "Fan off".
The relay module should turn on or off depending on the voice command.
