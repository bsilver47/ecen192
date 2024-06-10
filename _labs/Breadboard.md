---
title: Breadboard
number: 1
layout: lab
---

## Overview
Breadboards are tools to implement circuits in various contexts, and are especially useful in prototyping and development contexts. In addition to breadboards, we will be using LEDs and wires to create three circuits to better understand how they function.


## Background/Preparation
Breadboards function in different rows and columns, commonly referred to as busses. The busses that run along the long sides, for example, are referred to as the power rails. These are marked by the red and blue lines that are meant to help keep track of the positive and negative polarities of power supplied to the circuit.
Terminal strips are busses that run perpendicular to the power rails. These are marked by numbers on the ends of some of the terminal strips. They are also separated by the DIP (Dual In-line Package) Support, which allows for more complicated circuits and components. Traditionally, the non-power components are plugged into the terminal strips, which are, in turn, connected to the power rails by wires or resistors.
These busses are notable as they support connections without manually attaching every component. For example, if two wires or components are plugged into the power rail on one side that is marked with red, they are connected to each other. The same is true of each power rail and each separate terminal strip (again, marked by the numbers and separated by the DIP Support). Another way to picture the way this works is to look at the inside of the breadboard itself:

![Inside of Breadboard](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Breadboard.png/200px-Breadboard.png)



What we will be doing today is utilizing these principles to create various circuits.


## Equipment and Materials
- breadboard
- at least four LED lights
- at least four resistors
- wires to connect each component
- DIP Switch
- power source (battery and holder)

## Procedure
Start by plugging the red wire from the battery holder into the breadboard along the corresponding red power rail, along with the black wire from the battery holder into a hole along the blue power rail.
For our first circuit, we will create a circuit with one LED. Plug wires into each of the power rails and connect them to the resistor and the square LED by utilizing different terminal strips. The circuit should look something like this when you turn on the power source (the switch is on the back of the battery holder):

<picture>
    <img alt = "First circuit picture with one blue led" src="{% link images/blue-led.jpg %}" width="200">
</picture> 

Alternatively, to keep things cleaner, you can plug one end of your resistor directly into one of the power rails, rather than using more wires. This is a style choice, however, and does not make a notable change to the circuit. Either way, don't forget to take a picture! Note: if the circuit doesn't work as expected, try reversing the direction of the LED: as diodes, they only work one way.

<picture>
    <img alt = "Second circuit picture with one blue led" src="{% link images/blue-led-clean.jpg %}" width="200">
</picture> 

Next, we will create a traffic light! To do this, we will utilize a dipswitch placed over the DIP Support. While not always legible, the Dipswitch should have an arrow labeled "ON" that, while not necessary in orienting the component, will help with turning on and off the lights as desired.
Repeating the process from the one LED, place three other LEDs on the opposite side of the dipswitch to create a circuit that should look something like this:

<picture>
    <img alt = "Second circuit picture" src="{% link images/traffic-light.jpg %}" width="200">
</picture>

This is what it should look like using a dipswitch to turn on and off our lights!

<picture>
    <img alt = "Animated circuit gif of traffic light in different states" src="{% link images/traffic-light.gif %}" width="200">
</picture>

Don't forget to take a picture of your functioning circuits!
Lastly, make a new circuit according to your own design! This could involve different color LEDs, new layouts, and a different number of LEDs; so long as it is according to your own design!



## Post-Lab Work
Recall how the square LED was much easier to see, and much nicer to look at than the other LEDs. This is because of the way it diffuses the the light. For the post-lab, find an object at home that will work well as a light diffuser to put over one of your other LEDs. (Hint: Try to find something translucent. If it is too solid, the light won't be able to get through, but if it is too clear, the light won't disperse as desired).


## Rubric/Submission
Submit pictures of all three circuits with a brief explanation of any context you would like to give about your circuits.

