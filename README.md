# c172pSim

This project is for work on my home cockpit for the C172P (1982)  

**As of July 2023, THERE IS NO WORKING SOFTWARE or HARDWARE.**

Initial work on comunicating between a C++ program, Flightgear and Arduinos is in progress.

The cockpit will be used with FlightGear, an open source Flight Simulator.

The project will feature a C++ application which will run on Ubuntu Linux or a raspberry Pi. It will manage communication with the Flightgear Simulator and Cockpit hardware,   Data driving multiplexers, display controllers, stepper motor drivers, air-core drivers can be routed to Raspberry Pi gpio pins, or Separate Raspberry Pis orArduinos Arduino supported devices include Arduino Uno, Arduino Mega2560 and Arduino Pro Minis.

The main program in C++ will be called FSM.  This can be interpreted as either of the following:

- Flight Sim Middleware
- **[Flying Spagetti Monster](https://en.wikipedia.org/wiki/Flying_Spaghetti_Monster)**
