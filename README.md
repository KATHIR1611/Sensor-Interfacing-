# ULTRASONIC SENSOR INTERFACING
## AIM:
To measure the distance of the obstacle using ultrasonic sensor and display the value in LCD and serial monitor using Arduino UNO controller.
## Software required:
Arduino IDE </br>
Proteous
## PROCEDURE:
### Arduino IDE
Step1:Open the Arduino IDE </br>
Step2: Go to file and select new file option </br>
Step3:Type the program </br>
Step4:Go to file and select save option to save the program </br>
Step5:Go to sketch and select verify or compile options </br>
Step6:If no error Hex file will be generated in the temporary folder </br>
### Proteus
Step7:Open the Proteus software </br>
Step8:Go to file select new design and click ok button </br>
Step9:Select component mode and click pick devices from the library </br>
Step10:Type the component name in the keyword to select the components and click ok button </br>
Step11:Design the circuit as per the diagram </br>
Step12:Double click the Arduino controller and upload the hex file generated by Arduino IDE </br>
Step13:Click start button and check the output
## THEORY:
An Ultrasonic Sensor is a device that measures distance to an object using Sound Waves. It works by sending out a sound wave at ultrasonic frequency and waits for it to bounce back from the object. Then, the time delay between transmission of sound and receiving of the sound is used to calculate the distance.
The Serial Monitor is a part of the Arduino IDE. It is also available in the Web IDE. It allows you to send and receive data from the board connected via USB. This is using the concept of Serial Communication.
You can send the commands by typing in the window on the top and pressing 'Enter' or clicking 'Send'. The data from the board is displayed below that.
This is very useful when debugging the code, or if you need to give inputs to the board, This is probably the most useful tool in the IDE. The more you use it, the better you get at testing complex projects that takes inputs and provides consequent outputs.
Once you've uploaded the code, the board will begin to transmit data to the computer. You will know this when you see the Tx LED on the Arduino blinking each time it transmits a data. Now if you open the Serial Monitor, you'll see the distance being displayed.

## PROGRAM:

```

## CIRCUIT DIAGRAM:
## OUTPUT:
## RESULT:
Thus the distance of the obstacle is measured using ultrasonic sensor and display the value in LCD and serial monitor using Arduino UNO controller.
