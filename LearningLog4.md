# Learning Log 4
*For the week beginning 19/04/21*

## What have I done this week?
| Task | Time Spent (hrs) | Explanation | Link to resources |
| --- | --- | --- | --- |
| C++ contribution to collaborative project | ~14 | Created a sketch for an onboard flight controller of an RC plane. Processes wirelessly transmitted control signals for 2 servos and a motor | [Here](https://github.com/BMcrisium/Arduino-RC-plane/blob/main/RCFlightController.ino) |
| Circuit schematic for flight controller | < 1 | Used [circuito.io](circuito.io) to create an accompanying circuit schemaic for the flight controller sketch | [Here](https://github.com/BMcrisium/Arduino-RC-plane/blob/main/CircuitSchematic.png) |

## What have I learnt?
When I started to program the flight controller I came to realise a stepper motor would not be able to create the thrust needed to drive an RC plane.
So instead, the circuit was designed using a brushless motor connected to a electronic speed controller (ESC). The ESC can be connected to the board using a single pin, run on power from the arduiuno and controlled using the same code libraries used for servos.

I have also learned that the NRF24L01 RF Chip is a cheap, heavily documented radio transmitter / receiver well suited for use in an RC plane.
The component draws 3.3v of power which can be supplied directly from the arduino to transmit and receive data to 100m away.
It can also be programmed to create interrupts when receiving or transmitting data which is communicated to the Arduino using the IRQ pin which proved to be very useful when programming the sketch.

## Next Steps
I will continue to adjust the flight controller sketch to any feedback I may receive. Eventually, I hope to physically build the circuit so I can holistically test the sketch.
Outside of the collaborative project, I will continue to learn about the many different uses for an arduino. 
