## Software Quality Metrics - 2 

1. Coupling
	1. measure of inter-dependence between software components
		1. Loose coupling is good
		2. Tight coupling is bad
	2. Can occur from inheritance, message connections, and containment.
		1. Use strong information hiding
		2. Global data and shared memory increased coupling
		3. Avoid pointers
		4. Minimize data parameters.
	3. Impacts testability, maintainability, reusability
2. Cohesion
	1. measure of how single purposed/ well defined a component is
		1. High cohesion is good
		2. Low cohesion is bad
	2. can measure on the class level or the method level.
	3. Cohesion impacts testability, maintainability, and reusability.
3. Complexity
	1. Cyclomatic Complexity is a measure of how complex a software component's control flow is.
		1. It is calculated by counting the number of decision keywords, the number of and & or operators, and adding 1 to the total.
	2. Cyclomatic complexity impacts testability, maintainability, understandability, and reliability.
4. Structure
	1. Structured Programs have 0 knots
		1. ![[Pasted image 20241118144058.png]]
5. Information Volume
	1. Volume = { total number of operators + total number of operands } log2 ( number of unique operators + number of unique operands)