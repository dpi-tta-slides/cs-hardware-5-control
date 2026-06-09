---
marp: true
theme: default
paginate: true
---

# CS Hardware - Day 5

## Microcontrollers

![bg contain right](assets/microbit.jpg)

---

# Goal For Today

By the end of today you will:

- Understand what a microcontroller is
- Program a BBC micro:bit
- Connect software to hardware
- Build interactive embedded systems

![bg contain right](assets/microbit-board.jpg)

---

# Review From Day 4

Yesterday we learned:

- Integrated Circuits combine many components
- Oscillators create timing signals
- Digital systems use HIGH and LOW voltages
- Computers depend on clocks

![bg contain right](assets/555-timer-chip.jpeg)

---

# Review From Day 3

We learned:

- Capacitors introduce TIME
- RC circuits create delays
- Oscillators repeatedly switch ON and OFF

![bg contain right](assets/astable-multivibrator.gif)

---

# Review From Day 2

We learned:

- Transistors act like switches
- Logic gates make decisions
- Computers are built from billions of transistors

![bg contain right](assets/cpu-closeup.jpeg)


<!-- TODO: day 1 review -->

---



<!-- 

Curta Mechanical Calculator (1948–1972)


Looks like a strange mechanical artifact
Hundreds of moving parts
Entirely mechanical
The Curta was considered one of the best portable calculators before electronic calculators displaced it in the 1970s.

 -->

# The Calculator Problem

In the 1960s, every calculator needed custom hardware.

- expensive
- difficult to redesign
- lots of specialized circuitry

![bg contain right](assets/sharp-compet-cs-10a.jpg)

<!-- INSTRUCTOR NOTES

In 1964, Sharp introduced the world's first all-transistor diode desktop calculator, the Compet, CS-10A.

-->


<!-- TODO: more desktop calculators -->

---

# Just A Few Years Later

Calculators became:

- pocket sized
- cheaper
- battery powered
- widely available

What changed?

<!-- TODO: pocket calculator example images -->

---

# A New Idea

What if we built a computer that could be reprogrammed?

Instead of changing *hardware*, we could change *software*.

![bg contain right](assets/intel-4004.jpg)

<!-- INSTRUCTOR NOTES

The first commercially available microprocessor is generally considered to be the Intel 4004, introduced by Intel in 1971. 

The 4004 combined the functions of a computer's central processing unit (CPU) onto a single chip, which was a major breakthrough in computer engineering.

Originally developed for calculators made by the Japanese company Busicom.

-->

---

## Yesterday

One integrated circuit (IC) could generate a wave. (555 Timer)

## Today

One integrated circuit (IC) can be programmed to perform many functions. This is a microprocessor (CPU).

---

# Microprocessor

One chip could now perform many jobs.

The same idea eventually led to:

- calculators
- computers
- microcontrollers
- phones
- embedded systems

---

# Microcontroller

Microcontrollers went even further

> A complete computer on a single integrated circuit.

CPU + Memory + Inputs + Outputs

All on one chip.

![bg contain right](assets/microcontroller-chip.jpg)

<!-- 

Texas Instruments TMS1000
1974
Microcontroller

-->

---

# Look Around

How many computers are here?

<!-- 

Most people say:
laptops
phones
Slide

The actual answer is:
- thermostat
- projector
- smoke detector
- microwave
- coffee machine
- elevator
- car keys

-->

---

# Embedded Systems

Most computers today are not PCs. They are tiny specialized computers called embedded systems powered by microcontrollers.

- microwaves
- washing machines
- thermostats
- toys
- cars
- robots

![bg contain right](assets/embedded-systems.jpg)

---

# Meet The micro:bit

The BBC micro:bit is a microcontroller designed for learning.

Built-in:

- LEDs
- buttons
- sensors
- radio
- USB

![bg contain right](assets/bbc-microbit.avif)

---

# What's On The Board?

- 5x5 LED matrix
- Buttons A and B
- Accelerometer
- Compass
- Temperature sensor
- Radio

![bg contain right](assets/microbit-labeled.avif)

---

# Demo: Hello World

Display:

HELLO WORLD

on the LED matrix.

![bg contain right](assets/microbit-hello.gif)

<!-- 

TODO: show the block builder and micropython options

Mention the main loops (on start and forever)

-->

---

# Lab Breakout #1

## Name Badge

Create a scrolling name badge.

Requirements:

- Show your name
- Add an icon
- Customize the message

![bg contain right](assets/name-badge.gif)

---

# The CPU

The Central Processing Unit (CPU) is the "brain."

It:

- reads instructions
- performs calculations
- controls outputs

![bg contain right](assets/cpu-closeup.jpeg)

---

# Memory

Memory stores:

- programs
- variables
- sensor readings

![bg contain right](assets/ram-chip.jpg)

---

# Inputs

Inputs tell the computer what is happening.

Examples:

- buttons
- sensors
- switches
- microphones

![bg contain right](assets/button.jpg)

---

# Outputs

Outputs allow the computer to affect the world.

Examples:

- LEDs
- speakers
- motors
- displays

![bg contain right](assets/led-matrix.jpg) 

---


Imagine designing a traffic light

You need it to:
- switch lights at the right time
- detect button presses
- respond to emergencies
- coordinate with nearby intersections

<!-- TODO: image -->

---

You could build this using:
- transistors
- logic gates
- timers
- relays

But every new feature requires rewiring hardware.

Changing this behavior using software makes this much easier. This is where a microcontroller shines

<!-- TODO: image of old traffic light controller with relays -->

---

# Demo: Traffic Light

- Let's build a mini traffic light using the Micro:bit

<!-- TODO: image -->

---

# Lab Breakout #2

## Traffic Light

Create a traffic light using the Micro:bit, a breadboard, and LEDs

![bg contain right](assets/microbit-traffic-light.jpg)

---

# Key Takeaways

<!--

- Microcontrollers are computers on a chip
- Programs control hardware
- Inputs and outputs connect computers to the world
- Sensors provide information
- Timing still matters
- Embedded systems are everywhere
- Software and hardware work together

-->