# Learning Log 3
*For the week beginning 06/04/21*

## What have I done this week?
| Task | Time Spent (hrs) | Explanation | Link to resources |
| --- | --- | --- | --- |
| Debugging previous programs | ~3 | Went back through all sketches created over the course of this assignment and made sure they worked as expected | None used |
| 5V DC stepper motor Circuit | ~2 | Followed the tutorial to create a circuit that controls a motor using the AccelStepper library | [Here](https://lastminuteengineers.com/28byj48-stepper-motor-arduino-tutorial/) |
| RC hobby research | ~1 | Searched through forums to find the best RF transmitter and receiver for my use | [Here](https://howtomechatronics.com/projects/diy-arduino-rc-transmitter/) and [Here](https://create.arduino.cc/projecthub/tsaritsynskyyaa/making-arduino-based-rc-transmitter-of-usb-flight-simulator-c67a71) |
| Radio transitter sketch | ~2 | Wrote a sketch that transmits a single string wirelessly | [Here](https://randomnerdtutorials.com/rf-433mhz-transmitter-receiver-module-with-arduino/) |
| Radio reciever sketch | ~2 | Wrote a skecth that receives data transmitted over radio. Adapted to use an LED to indicate when data was being received | [Here](https://randomnerdtutorials.com/rf-433mhz-transmitter-receiver-module-with-arduino/) |

## What have I learnt?
The more complex a single project becomes the more likely it is for the code to not work the first time. This is especially the case with arduino programming 
as any potential problem in a circuit could be with the wiring, components or the code itself. In addition to this, the arduino IDE has no dedicated debugging tools other than error messages when compiling.
To try and improve this I have installed the vscode addon VisualMicro so I can write sketches within vscode and take advantage of its built in debugging tools.

Most DIY plane's are built using a smaller, lighter version of the arduino rather than the arduino UNO I have been using to cut down on weight. 
As both circuit boards have identical laouts with the same number of pins, any program made for one board should also be able to run on the other board.

## Planned changes to goals
Over the next two weeks, I plan to write and test the program responsible for the flight controller on the plane for a collaborative project. This program will take a wireless signal as an input and convert it into the relevant control signals to be sent to the motor and servos.
I will also create a circuit diagram indicating how the components should be assembled. The variables and functions of the sketch
will be described in an external document as well. 
