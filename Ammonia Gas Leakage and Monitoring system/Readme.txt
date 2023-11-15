///ABSTRACT///

The purpose of this project is to improve the existing observation methods for 
ammonia leaks to avoid accidents caused by the inhalation of excess ammonia. The 
leakage of ammonia gas is very dangerous and harmful to humans because it is corrosive 
(high concentration) and might cause burning to our face and somehow will direct cause 
death [1]. This project will improve unrelated measurement methods, which are fixed 
or mounted on walls, limiting the purpose of measuring only. The project incorporates 
Internet of Things technology to help monitor gas sensor readings (MQ-135) from a safe 
distance, locate areas or parts where ammonia gas is leaking based on pressure sensor 
readings, and include a precaution system (siren alarm & red and green LEDs) that acts 
as feedback and purging system that controls water pumps and fans as well as the 
solenoid valves to control ammonia gas inlet. It also has a GPS system that will pinpoint 
the location of any gas leakage. The project system focuses on the transfer of data from 
the sensing unit to the broker, where it is temporarily saved in the Blynk app, but can be 
stored for a long time and exported in the web ThingSpeak. The data is shown on a 
mobile and web application that allows users to monitor sensor readings. The data is 
sent to Blynk applications and the ThingSpeak protocol web via the NodeMCU, which 
reads data from inputs and outputs. The findings of the prototype testing revealed a 
working Blynk and ThingSpeak web application, with the metre providing precise 
latitude and longitude readings and the GPS system providing accurate latitude and 
longitude. This ammonia gas leakage detection and monitoring system has been created 
and tested satisfactorily. There are some recommendations for this project of ammonia 
gas leakage detection and monitoring system, including changing the gas sensor to MQ-
137 because the MQ-135 is an air quality sensor and not a fully ammonia gas sensor, 
and switching to a different platform for web application monitoring that has a low data 
transfer delay. 

///Objective///

1. To develop detection and precaution system of the ammonia gas leakage. 

2. To develop purging system for the ammonia gas leakage. 

3. To develop GPS system to locate the area of ammonia gas leakage. 

4. To develop monitoring system and to alert the workers or officials


//flows//

The scope of work of this project focuses on designing an ammonia gas 
leakage detection system and precaution system which detects the area parts of 
ammonia gas leakages and to prevent the accidents occur. At the same time, the 
scope of work also involves the development of purging system for the ammonia 
gas leakage. Next, GPS system is developed to locate the area of ammonia gas 
leakage. Lastly, the scope of work also includes the development of distant 
monitoring by using IoT that will be developed on Blynk apps and ThingSpeak 
Web to alert the workers or officials


