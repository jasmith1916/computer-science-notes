# Dynamic Binding

There are 2 different types that can be assigned to a variable in [[Polymorphism]]. There is the compile-time type (or static type) and the runtime type. The static type never changes but the runtime type of an object can change as the program runs. For example, an interface name Locomotive has a class called Car that implements it. If a variable b is defined such as `Locomotive b` and is then assigned `b = new Car()`. The Locomotive is the static type while the Car is the run-time type of b. When we declare `b = new Car()` we are utilizing Dynamic Binding.

[[Cast]]ing 