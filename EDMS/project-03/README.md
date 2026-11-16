# Project 03 – Custom Wheel (Double-Spoke Design)

## Overview

A customized wheel model developed in Siemens NX as part of the *Engineering Design and Material Selection* course at ETH Zurich.

Starting from a course-provided CAD model containing the basic wheel geometry, I designed and modeled a custom double-spoke configuration with five spoke pairs and ten spokes in total.

Unlike the previous guided exercises, this project involved developing my own spoke geometry and determining how to integrate it into an existing parametric model.

## Software
- Siemens NX

## Modeling Process

The custom spoke design was developed through the following steps:

- Designing a fully constrained, parametrically adjustable double-spoke sketch
- Using reference geometry, angular dimensions, and expressions to control the spoke layout
- Projecting existing circular edges to create accurate sketch boundaries
- Applying Boolean operations (*Subtract* and *Unite*) to modify the wheel geometry
- Creating a circular feature pattern with five instances at 72° intervals
- Resolving a pattern update failure by switching from the Simple to the Variational method

## Key Takeaways

This project highlighted the difference between defining a sketch geometrically and creating a valid feature from it. Even a fully constrained sketch requires correctly closed and selected profiles for extrusion.

I also gained practical experience troubleshooting feature dependencies and understanding how different pattern methods affect the regeneration of geometry.

Most importantly, the project gave me experience adapting an existing CAD model to accommodate a custom design rather than simply reproducing predefined geometry.

The resulting wheel is an educational CAD design and has not been independently validated for structural strength or manufacturing.

## Preview

<img width="847" height="837" alt="Custom double-spoke wheel designed in Siemens NX" src="https://github.com/user-attachments/assets/8b28604d-65b3-4e05-a17a-52074d296f26" />
