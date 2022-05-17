# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. **What does the ___word___ 'polymorphism' mean?**
    Polymorphism means take something can take many forms


2. **What does it mean when we apply polymorphism to OO design? Give a simple Java example.**
    Polymorphism in OO design means objects can access to the methods but the methods can be used to perform different tasks. For example in Java we could have a cat and dog animals who are accessing a talk method from an interface but when the cat talks it produces a string "meow" and when the dog talks it produces a string "bark".


3. **What can we use to implement polymorphism in Java?**
    We can implement polymorphisms by using interfaces to initalise methods.

4. **How many 'forms' can an object take when using polymorphism?**
    An object that is being used for polymorphism can take on an infinite amount of forms as each aplication of the object can be different.


5. **Give an example of when you could use polymorphism.**
    If you have two vehicles but with different engintion processes you could use an interface which has a method to start the engine but the method each vehicle will be different.


# Composition and Aggregation

6. **What do we mean by 'composition' in reference to object-oriented programming?**
    Composition means we have an object that is part of another object

7. **When would you use composition? Provide a simple example in Java.**
    An example would be if you had a car class and had a engine class as a property of the car class.

8. **Give a difference between composition and aggregation?**
    Aggreation is something is apart of a object but not necessary in definating that object, for example a car might have a radio but a car without a radio is still a  car.

9. **What is/are the advantage(s) of using composition/aggregation?**
    Composition and aggregation allows us to reuse code and it our code DRY, useful in java since Java does not have multiple inheritance.
    Testing can be made easier with composition since you can test the object seperately from the object it is apart of.
    It would easier to cahnge/refactor code since the code is being kept DRY there are fewer areas you could need to change.

10. **When using composition, when an object is destroyed, what happens to all the objects it is composed of?**
    When the object is destroyed the objects it is composed of still exist.

11. **When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?**
    When the object is destroyed the objects it is composed of still exist.