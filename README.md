# beginner_python_flower
# Rainbow Flower 

This project generates a beautiful rainbow flower pattern using Python's Turtle graphics and the HSV color model.
The design is created by drawing multiple circular arcs while gradually changing colors to produce a smooth rainbow gradient.

Features

Uses Python Turtle graphics for drawing

Smooth rainbow gradient created with the HSV color system

Repeating geometric patterns

Simple code structure that is easy to modify and experiment with

Key Idea

1. A loop repeats the drawing process multiple times to create petals.

2. Inside the loop, circular arcs are drawn using circle().

3. The HSV hue value gradually increases, creating a rainbow effect.

4. The rotation of shapes forms the flower symmetry.

Requirements

Python 3.x

Built-in libraries:

     1. turtle
     2. colorsys

   #  Radial Sunburst 

A generative art project created with Python's Turtle graphics that draws a mesmerizing radial sunburst pattern
Project Goal

The goal of this project is to explore:

1. Python Turtle Graphics

2. Generative Art

3. Geometric Pattern Creation

4. Loop-based drawing algorithms
How the Pattern is Generated

The design is created using a loop that repeats 122 times.

Each iteration:

1. Moves the turtle to the center of the screen.

2. Draws a line outward.

3. Creates a small circular arc.

4. Extends the line further.

5. Rotates slightly to prepare for the next ray.

Because the turtle rotates by 3° each iteration, the lines spread evenly around the center, forming a full circular sunburst.

# Virus
A generative art experiment built with Python's Turtle graphics that produces a chaotic geometric spiral pattern.
Project Idea

This project demonstrates how simple mathematical rules can generate complex visual patterns.

By continuously increasing:

1. the distance moved

2. the angle of rotation

the turtle produces an intricate web-like structure that resembles a chaotic spiral or geometric starburst.
How the Algorithm Works

The drawing is generated with two variables:

Variable and	Purpose
1.	Distance - the turtle moves forward
2.	Rotation - angle after each step

Each loop iteration:

1. Moves forward by 1

2. Rotates right by 2

3. Increases 1 and 2

This gradual increase causes the drawing to expand outward while rotating unpredictably.

The loop stops once the rotation value reaches 200.
