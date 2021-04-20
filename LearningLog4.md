# Learning Log 4
*For the week beginning 19/04/21*

## What have I done this week?
| Resource Used | Time Spent (hrs) | Explanation | Link |
| --- | --- | --- | --- |
| C++ contribution to collaborative project | ~14 | Created a sketch for an onboard flight controller of an RC plane. Processes wirelessly transmitted control signals for 2 servos and a motor | [Here](https://github.com/BMcrisium/Arduino-RC-plane/blob/main/RCFlightController.ino) |
| Circuit schematic for flight controller | < 1 | Used [circuito.io](circuito.io) to create an accompanying circuit schemaic for the flight controller sketch | [Here](https://github.com/BMcrisium/Arduino-RC-plane/blob/main/CircuitSchematic.png) |

## What have I learnt?
From additional realised, I came to realise a stepper motor would not be suitable for an RC plane due to their low speed and high power draw even while idle. 
Instead the circuit was designed using a brushless motor connected to a electronic speed controller (ESC) which can be connected to the board
using a single pin and controlled using the same code as a Servo.

I have also learned that the NRF24L01 RF Chip is a cheap, well documented radio receiver to be used in an RC plane.
The component draws 3.3v of power which can be supplied  directly from the arduino to transmit and receive data with up to 100m of range.
It can also be programmed to create interrupts when receiving or transmitting data which is communicated to the Arduino using the IRQ pin.

## Next Steps
I will continue to adjust the flight controller sketch to any feedback I may receive. Eventually, I hope to physically build the circuit so I can test the sketch holistically.
Outside of the collaborative project I will continue to learn about how to program an arduino to control a variety of components. 
