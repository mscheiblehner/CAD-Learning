# Project 03 – Custom Wheel (Double-Spoke Design)

## Overview
A custom wheel design modeled in Siemens NX as part of the *Engineering Design and Material Selection* course at ETH Zurich.

Starting from a provided wheel template, I developed a five-fold double-spoke layout with ten spokes in total. The focus was on creating a parametric design that could be modified through dimensional expressions and repeated features.

## Software
- Siemens NX

## Modeling Process
The wheel design was developed from the supplied base geometry. The modeling process included:
- Working with the revolved wheel rim and central hub
- Creating a fully constrained sketch for a double-spoke group
- Using reference lines, angular dimensions, and expressions to control the layout
- Projecting existing circular edges into the sketch to define precise boundaries
- Applying extrusions and Boolean operations to remove material and build the spokes
- Repeating the spoke geometry with a circular pattern: five instances at a 72° pitch angle
- Using the Variational pattern method to resolve a feature update issue encountered with the Simple method

## Key Takeaways
This project strengthened my understanding of parametric sketching, projected geometry, Boolean operations, and feature patterns in Siemens NX.

A key lesson was that a fully constrained sketch is not necessarily a valid extrusion profile: the intended material regions still need closed, correctly selected boundaries.

The design was created as a CAD learning exercise using a provided starting template. It has not been independently validated for structural strength or manufacturing.

## Preview
<img width="847" height="837" alt="Custom double-spoke wheel designed in Siemens NX" src="https://github.com/user-attachments/assets/8b28604d-65b3-4e05-a17a-52074d296f26" />

