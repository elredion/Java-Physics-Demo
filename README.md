# Java-Physics-Demo

Author: Travis Robbins

Environment: Java SE 8

This demonstration provides basic collision detection and response for simple 2D objects under the influence of gravity.
Ball objects are assumed to have equal mass and ignore friction, wind resistance, and other soft factors.

Usage: Left mouse click on panel will create a new ball object up to a max of 100


Integration method: Verlet integration split into two components, acceleration and inertia


Collision method: With and without impulse to create a stable at-rest state


Rendering method: Linear interpolation separate from physics methods


Known issues: 

-Ghosting at very high object speeds


Future considerations:

-Implement constaints

-Implement rotation and more complex objects

-AABB collision detection
