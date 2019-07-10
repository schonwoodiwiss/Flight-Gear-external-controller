# Flight-Gear-external-controller
Advanced Software Programming 2 course project
Project contributors: Schon Woodiwiss, Eyal Pascu
course led by Dr. Eliahu Khalastchi

///////////////////IMPORTANT/////////////////////
To use this software, follow the following steps:

1. Install FlightGear flight simulator on your computer.
2. Add included generic_small.xml file to "\FlightGear [version-number]\data\Protocol"
3.Open FlightGear, go to Settings tab, and add the following two lines to the text area in "Additional Settings"

--telnet=socket,in,10,127.0.0.1,5402,tcp
--generic=socket,out,10,127.0.0.1,5400,tcp,generic_small
 
4. Open runServer.bat
5. Open runClient.bat
6. Start FlightGear

for reference, please watch my project presentation video - https://www.youtube.com/watch?v=GjBtE226xtU
