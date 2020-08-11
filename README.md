# HomeAutomationUsingBluetooth
A Home Automation System using Bluetooth which controls home appliances with voice commands or text commands using an Android App.
This project exhibits the development of an easy, adaptable and protected Home Automation System based on a smartphone and a microcontroller where you can control your home machines through voice commands or text commands. The plan depends on a microcontroller Arduino UNO board, 4 channel Relay Module, HC-05 Bluetooth Module. The home appliances are connected to the I/O ports by means of relay switches. The interaction between the cell phone and the Arduino UNO board is remote and secured and is password protected so that only the user has access to the appliances.


I. COMPONENTS REQUIRED
1.	ARDUINO UNO
2.	4-CHANNEL RELAY MODULE
3.	HC-05 BLUETOOTH MODULE
4.	AC BULBS (BLUE & YELLOW)
5.	DC MOTOR
6.	BREAD BOARD
7.	JUMPER WIRES
8.	EXTENSION BOARD

II.	IMPLEMENTATION

The Google Android Application and Google Play service is used as a voice to text converter if we want to send voice commands. For sending the text commands IoTBoys android application is used. The Bluetooth module is connected to the smartphone and that particular module is selected as the primary robot in the application for sending the voice or text commands. The commands are then given to the smartphone (application) which transmits the data to the HC-05 module.
The Bluetooth receiver in HC-05 module receives the data transmitted from the smartphone. Subsequently this data is processed through the ATmega328 microcontroller present in the Arduino UNO. The Arduino board have different output ports which are connected to different home appliances through the 4-channel relay board. This relay board acting as switches and switches the home appliances ON/OFF as per the data processed through the Atmega328 microcontroller. For testing purpose we are using 2 25W, 240V AC bulbs connected to AC mains supply and a 5V DC motor connected to a 9V high watt battery. The appliances switches ON/OFF as per the commands given by the user.

Following actions can be done by giving voice/text commands:
•	Switch ON kitchen (blue) light.
•	Switch ON bathroom (yellow) light.
•	Switch ON all the lights at once.
•	Switch ON the fan (motor).
•	Switch ON all the appliances at once.
•	Switch OFF any particular bulb.
•	Switch OFF all the bulbs.
•	Switch OFF the fan (motor).
•	Switch OFF all the appliances.
