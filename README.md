This file is for making an automated wifi scale using a HX711 connected to 4 50kg load cells connected to ESP8266


About to test the configuration of the scale talking to ESP8266. Initially I am going to have it work standalone
	this will run on a very simple webinterface that can be connected to locally. Maybe later on will change it
	to a web server so measurements can be read remotely.

Status:
	have tested the configuration.io file. may be working?
	switching between DOUT = 5 and CLK = 4 and the opposite
		with DOUT = 4 && CLK = 5 ==== zero factor = 0;
		with DOUT = 5 && CLK = 4 ==== zero factor = 8388607;
			but the lbs never change with more weight on the scale.
