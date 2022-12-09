- SMART CAR PARKING SYSTEM


All steps to Build our Project:
 

Step 1: In this Project First, we make a model. After making the model, we made parking 
        slots, road for vehicles and made toll gates on both sides of the road.

 
Step 2: After making a model, we make a circuit diagram. After making circuit diagram, 
        we joined all components with Arduino board. When we are joined all components with 
        Arduino board, we compile code for Arduino board, after the compilation we got output 
        value in serial monitor. We are using Arduino IDE software for this compilation code. 
        In this output, we see all sensors are detected and servo motor working.
         
        We are using Arduino board, 8 IR sensors, 2 servo motors (using toll gates), jumper 
        wires, bread board and ESP8266 Node MCU.

Step 3: After the compilation of Arduino code, we are using ESP8266 Node MCU. First, we are opened 
        the web of Blynk io and register blynk io web. After the registration, open the mobile app 
        Blynk Iot and create a device, after creating the device, select thehardware and connection 
        type. After this creating all connections, go to developer mode and top right side ‘+’ button 
        available. Press the ‘+’ button, open the widget box. After the opened the widget box, select 
        the TAB option. When select the TAB option, we are creating two tabs for two parking space 
        (Parking 1 & Parking 2). 

        In Parking 1 tab, we are going to again widget box and select the 3 times 3 led. The first 
        Led1 name is slot1 and select the virtual PIN(V10). Same time we put the led 2(slot 2-
        V11) and led 3(slot 3 -V12). 
 
        In parking 2 tab, we will select Led in front like parking 1 and select different virtual pin 
        number (V13, V14, V15).

Step 4: Now we are doing connected the ESP8266 Node MCU after the setup work in Blink app. The device 
        created in Blynk IO, then we goes to device info and copy the auth token. After the auth token 
        copy, go to ESP8266 code and copy the auth token code.we put our mobile hotspot device in the 
        code with wifi name and password.
 
        We compiled the ESP8266 code then ESP8266 connecting the mobile hotspot. After connecting open 
        the serial motor and see the slot is empty then output ‘0’ and car go to parking then slots 
        value is ‘255’.While opening the Blynk IOT mobile app,we see the parking slots empty and full.  



-Refernce:

[1] https://apps.apple.com/in/app/blynk-iot/id1559317868
[2] https://github.com/blynkkk/blynk-library/blob/master/src/Blynk/BlynkTimer.h 
[3] https://docs.blynk.io/en/legacy-platform/legacy-articles/nodemcu







