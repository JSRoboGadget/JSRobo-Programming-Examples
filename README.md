# JS_ROBO_GADGET
Programming IoT with Javascript

Welcome to JSR-Gadget

"JSR-Gadget" stand for JavaScript Robot controller gadget.
The intention is to create a multipurpose Automation platform with the use of a self-made Robot controller device. 
It will be able to control a 5DOF Robot arm + the tool and all the peripheral devices attached to it.

This first version is a Prototype version where a micro-controller is use at this moment, 
The end goal is to use a more powerful but affordable hardware in order to do Home or small industry Automation. 

I have ready a 3DPrint robot with the use of hobby PWM digital servo motors, so the precision of the mechanic is less than ideal 
but it meets the purpose of a Educational Robot arm.

In the other hand the software created like the 3DCad view robot work space and the Programming editing functionality as well as the control loop had a full functionality able to handle precision of less than 1mm and control motion speed from 0 up to 600 mmm/s at this stage is only open loop.

The main part is the Robot Controller Gadget, this device is able to:

- Execute high level line statement commands for kinematic motion like Move from Point [A] to Point [B] in a linear path or Joint mode.
- Create Conditional loops with user defined timer, delay ,or virtual inputs states (created from a PC HMI for example)
- Create GoTo and Label statements for control program flow execution.

In this Repository you will find 
- User create examples for the Line statement programing commands.
- Detail documentation of every command 
- Documentation on How to do expand the functionality of the provided user interface (HMI), create new control or simulation modules.

That's all for now, Have fun and enjoy the learning journey!
