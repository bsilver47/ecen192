---
title: Breadboards
number: 2
layout: lab
---

## Overview
Breadboards are tools to implement circuits in various contexts, and are especially useful in prototyping and development contexts. In addition to breadboards, we will be using LEDs and wires to create three or four circuits to better understand how they function.

<picture>
    <img alt = "Picture of a breadboard" src="{% link images/front_breadboard.jpg %}" width="200">
</picture> 



## Background/Preparation
Breadboards function in different rows and columns, commonly referred to as busses. The busses that run along the long sides, for example, are referred to as the power rails. These are marked by the red and blue lines that are meant to help keep track of the positive and negative polarities of power supplied to the circuit.
Terminal strips are busses that run perpendicular to the power rails. These are marked by numbers on the ends of some of the terminal strips. They are also separated by the DIP (Dual In-line Package) Support, which allows for more complicated circuits and components. Traditionally, the non-power components are plugged into the terminal strips, which are, in turn, connected to the power rails by wires or resistors.
These busses are notable as they support connections without manually attaching every component. For example, if two wires or components are plugged into the power rail on one side that is marked with red, they are connected to each other. The same is true of each power rail and each separate terminal strip (again, marked by the numbers and separated by the DIP Support). Another way to picture the way this works is to look at the inside of the breadboard itself:

<picture>
    <img alt = "Picture of the inside and back of a breadboard" src="{% link images/back_breadboard.jpg %}" width="200">
</picture> 

What we will be doing today is utilizing these principles to create various circuits.


## Equipment and Materials
- breadboard
- at least four LED lights
- at least four resistors
- wires to connect components
- DIP Switch
- power source (battery, connector and screw terminals)
- (optional) button
- (optional) buzzer

## Procedure

Start by inserting the red and black wires into the screw terminals and tighten the screws so that you can connect the battery to the breadboard easier.
Once that is done, you will be able to set up the first circuit. Do this by connecting the screw terminals to the power rails, as well as a resistor from one of the power rails, and a wire from the other. The other end of each should be plugged into neighboring terminal strips, along with the blue (square) LED in each of the terminal strips to connect them. If, when everything including the battery is plugged in as described, the LED does not light up, this is likely because of the LED itself. Light-Emitting Diodes, LEDs, like all diodes, are unidirectional. Our LEDs are less sensitive than other diodes, so if plugged in the wrong way, there is less risk of breaking, but the solution, just the same, is to reverse the direction. This is what the first circuit should look like.

<picture>
    <img alt = "First circuit picture with one blue led" src="{% link images/circuit1.jpg %}" width="200">
</picture> 

Next, we will build a circuit like a traffic light. To do this, we will utilize a dipswitch placed over the DIP Support. While not always legible, the dipswitch should have an arrow labeled "ON" that, while not necessary in orienting the component, will help with turning on and off the lights as desired.
Repeating the process from the one LED, place three other LEDs (ideally red, yellow and green for the traffic light effect) on the opposite side of the dipswitch to create a circuit that should look something like this:

<picture>
    <img alt = "Second circuit picture" src="{% link images/circuit2.jpg %}" width="200">
</picture>

The third circuit is optional, but involves a button and a buzzer. The setup is much like the other circuits, but, with the involvement of the button, it will be more difficult to tell whether it is setup and oriented properly. For this reason, we will reuse the square LED from the first circuit so that we can tell with certainty that it works. The circuit itself should look like this.

<picture>
    <img alt = "Animated circuit gif of traffic light in different states" src="{% link images/circuit3off.jpg %}" width="200">
</picture>

When the button is pressed, it should look like this and play a sound.

<picture>
    <img alt = "Animated circuit gif of traffic light in different states" src="{% link images/circuit3on.jpg %}" width="200">
</picture>

Lastly, make a new circuit according to your own design! This could involve different color LEDs, new layouts, and a different number of LEDs, as well as buttons, switches, or even a buzzer; so long as it is according to your own design!


## Optional Out-of-Class Activities
Recall how the square LED was much easier to see, and much nicer to look at than the other LEDs. This is because of the way it diffuses light. For the post-lab, find an object at home that will work well as a light diffuser to put over one of your other LEDs. (Hint: Try to find something translucent. If it is too solid, the light won't be able to get through, but if it is too clear, the light won't disperse as desired).


## Rubric/Submission
Submit pictures of all three or four circuits with a brief explanation of any context you would like to give about your circuits.

