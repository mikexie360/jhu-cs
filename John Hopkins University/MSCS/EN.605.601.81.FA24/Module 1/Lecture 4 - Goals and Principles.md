# Goals and Principles

## Goals of software engineering

- Modifiability
	- Make software easy to change without defects
- Efficiency
	- Optimize speed and memory usage.
- Reliability
	- How long will the software run before it breaks. Mean time to failure.
- Usability
	- Is the software useful? Is the customer satisfied with the software?

## Software Engineering Principles
- Modularity
	- The best way to reduce complexity is to reduce the number of things that needs to be connected
	- Instead of looking at lines of code, we should look at the program as a collection of modules or components.
		- Modules can be procedures, functions, classes or packages.
		- Divide and Conquer. If a problem is too big to solve, break it down into smaller problems. Once you solve all the easy problems, combine them to solve the bigger problem.
	- Random / Accidental Modulization, is a bad form of modulization.
		- A remote control is a modular component, a TV is a modular component, a table is a modular component. 
		- But if a randomly decide to use a hacksaw and split my TV into two separate components, it wouldn't be very useful.
		- Each component should have its own function and purpose. You shouldn't modulate without some purpose. You shouldn't break components down for the sake of creating smaller components.
	- A module should have a single purpose and be cohesive.
- Abstraction
	- A module should be simplified
	- Suppresses with unneeded details
- Encapsulation
	- High Cohesion
		- We want to maximum cohesiveness.
		- Everything inside a module should be useful
		- A module should have a single purpose.
	- Low Coupling
		- A module should have well defined connections
		- A module should hide its complexity and provide a simple interface.
- 4 C's: Correct, Complete, Consistent, Confirmable
	- Correct
		- No bugs
	- Complete
		- Completely satisfies the requirements and needs of the user
		- No missing features
	- Consistent
		- Have some sort of standards and convention
		- Make it look like as if one person created it, even if though multiple people may have worked on it.
	- Confirmable
		- It should be possible to demonstrate that the software is correct through tests or proof of correctness.
- 