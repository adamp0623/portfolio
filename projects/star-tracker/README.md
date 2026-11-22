# Two-axis star tracker | STM32 pointing mount

[Back to portfolio](../../README.md)

I built this because I wanted a more direct way to find celestial objects in the night sky. I could look up an object's coordinates, but I still had to work out where to look. The mount uses two stepper motors and an STM32 to point a laser in the direction of a selected object.

## What I built

- Designed and assembled a custom mount with two motorized axes.
- Integrated the control electronics and stepper motors.
- Wrote STM32 firmware in C to turn a target's right ascension and declination into motion on the two axes.

## What I tested

I field-tested the assembled system to check that the firmware and mechanical axes worked together. This was a pointing prototype: the goal was to direct attention toward a selected object in the sky.
