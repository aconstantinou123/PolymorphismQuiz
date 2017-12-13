# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
  The state of having many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
  The ability of a language to allow an object to have various types/classes e.g. in Java a Class Monitor could have a Super Class Visual Input and an Interface - IOutput

3. What can we use to implement polymorphism in Java?
  An object can inherit a super class/abstract class an implement an Interface

4. How many 'forms' can an object take when using polymorphism?
  Unlimited?

5. Give an example of when you could use polymorphism.
  In a game a designer could create a class called Enemy. Subclasses could then be created for each individual enemy e.g. Zombie. These would share properties with their parent class but could have their own attributes, methods (completely different or overridden/ overloaded). The subclasses of enemy could also implement different interfaces if they require different methods. A Zombie class would therefore have a Zombie type, Enemy type as well as any interface types.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
This is where an object contains a "has a" relationship with another object. For example a Person class could include a Job class within it e.g. Person person = new Person(name, job). Job would be its own class so a Person object would be composed of a String name and an instance of the Job class.

7. When would you use composition? Provide a simple example in Java.
See above. Another example would be a Car class. Car could be composed of an Engine class, Driver class, Wheel class etc

8. What is/are the advantage(s) of using composition?
We can reuse these classes in other programs/classes e.g. Truck class could also have a relationship with engine class. Using composition allows us to keep access to subclasses private.


9. What happens to the behaviours when the object composed of them is destroyed?
The behaviours are destroyed as well
