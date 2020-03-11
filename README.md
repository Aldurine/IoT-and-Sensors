# IoT-and-Sensors
I have integrated a large number of sensors with different IoT modules

1)NODE MCU and PIR SENSOR with BLYNK:
This can be implemented very easily as the base code is available in the examples it self.
First download the Blynk libraries https://github.com/blynkkk/blynk-library,and in the Arduino IDE go to Sketch>Include Libraries and give .AddZipFile>then select where the file exists.So the library is added to your IDE now go to file>examples>blynk>Boards_Wifi>NodeMCU.
You get an example code.
Now download the Blynk App in your smartphone.Login/Signup using your credentials and give new project.While creating new project it asks for the board.Choose NodeMCU and give a project name for your project and hit create.An authentication token will be sent to your email-id.
Do not Loose This at any cost!!!
In your IDE there put your authentication code under auth[] and put your Wifi name and pass word of your phone too.
In Blynk swipe left,we get to see a lot of widgets select Gauge and Notification.
The widgets are added to your project pane,now tap on Gauge set the input pin as V1(VIRTUAL PIN).
Switch on your mobile hotspot,do the circuit and compile the code.
