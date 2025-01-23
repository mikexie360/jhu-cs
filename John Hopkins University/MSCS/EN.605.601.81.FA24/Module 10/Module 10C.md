## Implementation

### Hand-Crafted Code

Make cabinets from scratch with lumber

using sticks to build cabinets would be similar to making code line by line.

vs. 

### Reuse 

Use pre built cabinets and put them in a specific design

Using pre built cabinets, would be like using pre built components for software.

### Defect Prevention

Bugs exists in software, because programmers put them in there.
Best way to avoid bugs, is to not program.

Don't build software line by line.

Build software by components.

### Components Reuse

Components are like bricks

Hand crafted code is like mortar.

You need both, but most of your software is made up of components.

### Framework reuse

Reuse partially built software, but we need to fill in the holes.

We tailor a framework and fill in our own details.


### inversion of control

in component reuse
the code we write is in control.

in framework reuse
The code that we reuse is in control.

### Levels of Reuse

- Clear box reuse
	- We can see and make changes to the code.
	- We can tailor it to our own needs.
	- Once we change it, we own it.
- Translucent box
	- Combination of both
	- We can see it and use it but we can't change it.
- Black Box
	- We can't see the code.
	- We only have access to the specification
	- Easy to swap between version.