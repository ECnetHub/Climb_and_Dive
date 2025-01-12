---
title: FAQ's
layout: default
nav_order: 7
---

## **Climb_and_Dive** ##
{: .text-blue-100}
{: .text-right}

## Frequently Asked Questions ##

**Does the Climb_and_Dive work with any ESC?**  The timer does require an ESC with a built in BEC (battery eliminator circuit).  Other than that, the timer should work with just about any ESC but there may be some rare ESC's out there that may not be compatible.

**Can I extend the touch sensor pin?**  Yes, in theory.  You will have to experiment to make sure it works reliably, but you can add a wire to the touch sensor pin to extend the ‘sensor’ to another location.

**Why don't I get the  one second throttle 'blip' when I start the timer?**  If your ESC has a procedure for throttle calibration, try that, it may help.  See [ESC Information](Power System Information#ESC Information).

**The motor takes to long to get to cruising speed after take-off**  Do not hold the running airplane for an extended period before releasing for take-off.  There is a 5 second delay after the motor reaches the programmed flight RPM until the active function of the timer becomes fully operational.  This is to prevent the active function from impeding the airplane climb-out and acceleration to cruising speed.

**Is a Bluetooth wireless connection allowed in competition?**  The Bluetooth radio is turned on *only* while the timer is in the programming mode.  Therefore the Bluetooth connection cannot be construed as to provide any control of the aircraft during flight.  Bluetooth is 2.4GHz spread spectrum technology.  The timer uses low energy Bluetooth transmitted through a very small onboard antenna which limits it's usefull range to about 30 feet, or 10 meters, maximum.

**Is Bluefruit Connect the only app that will work with the timer?**  No, there are plenty of other free Bluetooth apps that support wireless UART communication.  Bluefruit Connect was suggested for its simplicity and ease of use.

**Can I make a housing for the timer to help protect it?**  Of course, but making it completely weatherproof may be a challenge.  If you have access to a 3D printer you can download STL files for a casing and cover [here][4].

**What type of solder do you use for the backpack PCB assembly?**  The backpack components are soldered with a RoHS compliant lead-free synthetic no-clean formula solder paste.

**What is bootout.txt on the `CIRCUITPY` drive?**  This a small text file that is automatically generated by CircuitPython.  It includes information on which version of CircuitPython is installed as well as details about the microcontroller board.

**What version of the program code do I have installed?**  The software version is included in the device name that appears on the Bluetooth app window when you connect to the timer.

**What is CircuitPython?**  CircuitPython is Adafruit's fork of the MicroPython programming language.  Micropython is a subset of instructions derived from Python specifically for use on microcontrollers.  CircuitPython is well supported and a tonne of information can be found in various [Adafruit learning guides][2].

**Can I make changes to the program code?**  Yes, Adafruit and CircuitPython make it easy.  If you are making minor changes, open code.py in any text editor program, like Notebook or TextEdit.  Make your changes and then save it as code.py back onto the `CIRCUITPY` drive.  As soon as the code is saved the program re-boots and your new code starts running.  If you would like to make more substantial changes then I would suggest a free code editing program like [Mu Editor][1].  The [Adafruit Learning Guides][3] cover everything you need to know.


[1]: https://codewith.mu/en/about
[2]: https://learn.adafruit.com/welcome-to-circuitpython
[3]: https://learn.adafruit.com/welcome-to-circuitpython/creating-and-editing-code
[4]: https://github.com/CircuitFlyer/Climb_and_Dive/tree/main/Design%20Files/Casing
