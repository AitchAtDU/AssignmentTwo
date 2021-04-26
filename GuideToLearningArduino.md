# Learning to Program Electronics
Pic of an arduino uno behind the logo for arduino  
__A guide on starting off with Arduino programming__ *by z-code*

## Introduction
Arduino is an open-source electronics programming platform ~~etc etc etc~~.  
Putting it simply, this platform consists of two parts:
1) Hardware
2) Software

The organisation is respopnsible for the co-ordination of these two sides to create an environment where circuits can be desingned and contolled by a program running on a single circuitboard. Enabling the versatility that makes it such a powerful tool.

Arduino's are suitable for suitable for anyone 13+ almost entirely regardless of any previous experience. This guide is for anyone who fits this criteria, is intrigued from the opening description and would like advice on how to start.


## What prior knowledge do you need?
As stated earlier, learning to program for an arduino is very approachable. The main language used is C++ is the main language used for writing programs. Should be have knowledge on some of the basic principles of programming. While it is not necessary being familiar with the basic syntax used in C languages will help remove a lot of the frustration that comes along with starting to learn the skill. To get more acquianted with C++ as a whole, the codeacademy tutorial [here](https://www.codecademy.com/learn/learn-c-plus-plus) is a great place to start.

If you haven't had any experience with electronics that is also ok! Almost all online tutorials come with circuit diagrams that are straight forward to follow regardless of your familiarity. For an initial guide on how to create circuits using a breadboard, I recommend reading through this article [here](https://learn.sparkfun.com/tutorials/how-to-use-a-breadboard/all)

## Why learn Arduino Programming?
If you've ever been curious about how every day electronics work then there's no more approachable way of getting hands on experience with the inner workings of electronics. Have you ever wondered how your phone communicates with a card reader when you use contactless payments? What about how sound is recorded and stored digitally. While you could always find out find out from an online article or by scrawling through forums, experimenting with the technology can be a much more engaging and enriching experience.   
If you've ever looked at a device and wished it had some extra funuctionality then why not just make your own version? Programming and circuit building is such a creative and versatile skill the limit to the circuits you can make is laregly bound by your imagination and motivation to learn (Cheesy but true)

Why not just use a PC? Devices that need to be portable. Easier way of directly interfacing with hardware. If you've veer been curious about how the electronics you use every day work.

If this aspect of programming arduinos is of particular interest to you then you're in luck! A huge subset of engineering is comprised of electronics engineers who are responsible for designing and developing electrical systems for industry. As the world turns to automate jobs more and more, this sector is only expected to become more and more important.

Even if you don't find this prospect particularly appealing, learning C++ can still be beneficial to a potential career in programming. Despite it's age, C++ is still widley used in modern life. Most languages share common features or are based on C++ in some form, learning to program an arduino will improve your general programming ability.

## So, how do you start?
The first step is to purchase an Arduino microcontroller. There are many choices from different types of boards that Arduino offers, the most readily available, popular and cheap is the Arduino Uno. As a result, it also has the most documentation making it perfectly suited for beginners. While Arduino do produce and sell their own circuit boarads, there are many third party variations made by other manufacturers that are functionally identical but much cheaper.

Many online electronics retailers offer kits that bundle together everything a beginner might need to begin programming an arduino including the circuit board itself, a breadboard, wires and a variety of components to build almost any type of circuit. While this can seem a bit overwhelming at first, having all of the components you need gives you the freedom of being able to customise and experiment with circuits to your hearts content. [Here](https://www.ebay.co.uk/itm/RFID-Learning-Starter-Kit-Set-Arduino-UNO-R3-Upgraded-Version-Learning-Suite-Ace-/163826363177) is a link to the kit I purchased when starting my journey. Can always buy additional components seperately as required.

So that's the hardware covered, now for the software. Arduino offers their own integrated development environment (IDE) that contains all the basic features that you might need to write your first program. As you begin to write larger programs you may want to consider using a more feature rich development environment. Thanks to the arduino being open source, there are plenty third party options to choose from. I can recommend the [arduino extension for VS code](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) which can integrates with git seamlessly and provides additional debugging toold to figure out why a program isn't working as expected.

## Software of an Arduino
So what does the program that runs on an arduino look like? To answer that here is an annotated program taken from Arduino's official set of examples:  
```
void setup() {  
   pinMode(LED_BUILTIN, OUTPUT);
}
```
>The setup function is executed once when the arduino is first powered up.
```
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}     
```
>As soon as the setup function is executes, the loop function is ran repeatedly until the arduino loses power or is turned off. 

## Hardware of an Arduino
UNO is based on a 8-bit atmega processor.
Runs at 16MHz with 32KB of storage and 2KB of RAM. Miniscule even compared to the specs of modern phones making the Processing power the largest limitation of the UNO. However, this is all that's required for most of the circuits you may want to create. The board contains more than just a processor however:

Zoomed in on the pins for labelling with extra colour coded information about the use of each pin.
Also include information about the 5v DC power in and the usb header. Pins 0 and 1 are the serial pins, can be used for a second usb

## Helpful Resources
There are so many helpful resources online available for learning how to program an arduino.  
- Arduinos own website
- Howtomechatronics is an example of a youtube tutorial channel great for finding inspiration for a project.
- Some of the others that I have used and linked to throughout the project

## Gloassary of Terms
One thing that can deter new users away from learning how to program an arduino is all of the new terminology - can seem daunting. Here is are is a gloassary of some of the most frequently used terms:

## Evaluation of My Experience
Round up my experience with programming an Arduino. Was it worth it for me? Will it be worth it for the audience?

If you've made it this far into this guid then I'm willing to bet that you'll benefit from learning to program an arduino in one way or another.
