# Project 03 – Custom Wheel (Double-Spoke Design)

## Overview

A custom wheel design developed in Siemens NX as part of the *Engineering Design and Material Selection* course at ETH Zurich.

Starting from a course-provided wheel base containing the initial rim and hub geometry, I independently designed and modeled a double-spoke configuration featuring five spoke pairs and ten spokes in total.

The project focused on developing the spoke geometry, defining its parametric relationships, and integrating the design into the existing CAD model.

## Software
- Siemens NX

## Modeling Process

The custom spoke design was developed through the following steps:

- Designing a fully constrained, parametrically adjustable double-spoke sketch
- Defining geometric relationships using reference lines, angular dimensions, and expressions
- Projecting existing circular edges to establish precise connections between the spokes, rim, and hub
- Using Boolean operations (*Subtract* and *Unite*) to modify the base geometry and construct the spokes
- Applying a circular feature pattern with five instances at 72° intervals
- Resolving a pattern update failure by switching from the Simple to the Variational method

## Key Takeaways

This project demonstrated the importance of translating fully constrained sketches into valid 3D features. Even when all geometric constraints are satisfied, extrusion requires correctly defined and selected closed profiles.

I also gained practical experience troubleshooting feature dependencies and selecting suitable pattern methods when working with interconnected geometry.

Compared with my previous guided CAD exercises, this project involved greater independence in geometric design and modeling decisions.

The resulting wheel is a CAD learning project and has not been structurally analyzed or validated for manufacturing.

## Preview

<img width="847" height="837" alt="Custom double-spoke wheel designed in Siemens NX" src="https://github.com/user-attachments/assets/8b28604d-65b3-4e05-a17a-52074d296f26" />
