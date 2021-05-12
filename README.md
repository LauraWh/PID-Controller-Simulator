# PID-Controller-Simulator

This code was written by Laura Whelan (c17303991@mytudublin.ie) as part of a Final Year Project in DT021A.

This project will use an example of temperature control to illustrate PID control with an interactive interface. 
This simulator has been created so that it can be used in a website browser. 
It is also available at this link: http://eleceng.dit.ie/dsp/elab/pid/

The system visuals consist of a tank of liquid, a window and a radiator. 
The control system will be used to get the liquid in the tank to a desired temperature or "set-point". 
The set-point can be set on the image of the tank using the red arrow on the tank temperature scale.

The temperature of the liquid in the tank will be influenced by the opening of the window or the dial position of the heater. 
These elements of the simulator will be interactive as it will be possible to "drag" the window open using the mouse, or turn a knob to adjust the temperature of the radiator.

The temperature control will be done using PID control. 
It has three main components, Kp, Ki and Kd, which can be adjusted using sliders, or have the values typed into the interface. 
Other sliders will be used to control other parameters such as noise, as well as provide alternative methods to control the set-point, window and radiator. 
There is also a slider to set what time disturbance occurs to the system.

The temperature of the system will be represented using plots showing the temperature against time. 
The plot can be updated with the current control parameters by clicking the "update plot" button.

There will also be a block diagram of the system, showing the transfer functions and influence of disturbance and noise. 
The Laplace representation of each of these blocks can be revealed or hidden by clicking on the "toggle" button.

In each section there are help buttons indicated by question marks, that offer additional information about that section of the online PID simulator.
