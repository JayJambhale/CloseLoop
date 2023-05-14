# CloseLoop
Code for Close loop speed control

Given code is Arduino Code for close loop speed control of BLDC Motor using PID Controller.
For Throttle control of Kelly Controller , DAC MCP4725 used.
Motor used is of 500 W, 3000 rpm, Rated Torque - 1.6 N-m

For operation:
1. Connect the output terminals of the digital-to-analog converter (DAC) to the throttle 
input of the motor controller. Connect the VCC pin to the variable terminal and the 
DAC ground to the throttle terminal ground.
2. Connect a 10V DC power supply to the encoder's VCC and ground pins.
3. Connect the encoder signal pin to Arduino D2 pin.
4. Open Arduino IDE and upload the program on Arduino UNO.
5. Turn on 10 V DC power supply to encoder.
6. Set Demand and input torque values. Observe the response for each load in steps on the serial plotter of Arduino IDE.
7. After observing the responses, reduce the load on the motor to 0 N-m. Then Turn of the motor supply and then Mains Supply.

