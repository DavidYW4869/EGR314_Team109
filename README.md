# EGR314_Team109
The team will be constructing a plant pot addition that will have individually addressable LED Strip for plant lighting using red, green, or blue lights. 3 Individual buttons will be connected to a parallel-in, serial-out shift register to detect which button is pressed, and it will change the color of the LED strip accordingly. There will be a custom made moisture level sensor to detect the water level of the plant and will send the moisuture level (low or high) to the ESP 32 to monitor and display the values. Along with this, the pot addition will have a "pet defense system" that will be made using a motor, a water bottle, and an ultrasonic sensor that detects when a target is within range, triggering the spray bottle.

MPLab and Arduino are used for the project. Both need to be downloaded to run the project. 

In order to run the project, first add an ADCC peripheral in MCC in MPLabs, configure the pins, the modules, and each peripherals accordingly. Next, build and compile the code to a PIC18F23Q47. Once the code is compiled on MPLab, flash the ESP 32 code to an ESP 32 module.

Note: since there is an interrupt that would trigger when the moisture level is too low, it would be ideal to test all the functionalites of the system after submerging the moisture probes underwater. 

