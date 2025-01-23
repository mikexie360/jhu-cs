## Sample design pattern


- Singleton
	- Used when a single instance of a class is instantiated.
	- Provides a single point of access to that object.
	- Class constructor is not made public
		- Protected access
	- Static variable named instance.
		- Only one instance of it exists.
	- Static method returns a pointer to a unique instance object or makes one if it hasn't already.
- Facade
	- Provides a unified interface to hide a more complicated system.
	- Use a class or object to interface instead of a complicated system.
- Observer
	- When one object needs to notify other objects that its state has changed.
	- Subject class notifies others.
	- Observer class wants to be notified of state changes.