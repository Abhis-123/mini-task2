
## Project 1:
 #### Problem Statement:
 Own GPS Transmitter with the HC-12 Transceiver .Means Creation of a tracking device in which we don't need the cellular network  .

 #### Initial ideation:-
 For this project we need two transrecievers  to transmit data between two parts of the project ,a gps module ,battery and a Aurdino Uno 3 .GPS coordinates can be transmitted to remote locations simply with a GPS receiver. Remotely transmitted coordinates need to be received by a second transceiver, then processed with a computer or microcontroller (Aurdino Uno 3).
 
 #### Pipeline:
Steps: Powersupply=>Connect GPS Reciever => Refining Data=>Transmit Data(refined)=>Recieve Data=>Use Data On live maps.
 
Step| Solutions available | Advantages | Disadvantages
--------|---------------------|------------|--------------
 1.Power Supply                  |Battery                             | It is the only possible solution for continuous supply  
 2.GPS reciever                   |1.SparkFun Electronics GPS-14030<br/>2.Ublox NEO-M8N GPS Module|1.it is a cheap product <br/>2. it more gives data then GPS it can operate from -45 degree celsious to 105 degree  clesious|1.It is a product  with less number of facilities it gives less data with smaller boud rate<br/>2.It is 4 times in price then above one
3.Refining Data |1.Aurdino Uno 3  <br/>2.Teensy 3 | 1.It is a easily avilable product and cheaper product<br/>2.it is faster then Aurdino uno |2.It is coslier then Aurdino|3.Transmitting data and recieving |1.Mobile  transmission<br/2.HC-12 transreciever|1.it is easily avilable <br/>2.it is cheaper product and works upto one Km|1.It doesn't work for long distances|
4.Map|1.Google maps<br/>2.bing Maps|1.It is avilable on all divices<br/>2.It highly accurate as compared to google  maps|disadvantage of both is that they dont work without internet|

#### Final ideation
So finally taking the budget into account we are choosing following products 1.SparkFun Electronics GPS-14030,2.Aurdino Uno 3.HC-12
and the final cost will be around 60$(4+11+45)  connect battery(we can choose any from 3-7 volt)  to GPS ,aurdino and HC-12 transreciever in such a way that data from gps should be refined in Microconttroller (Aurdino) and then
