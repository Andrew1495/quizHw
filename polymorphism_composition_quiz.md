# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
    Many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

    Polymorphism in java reference to instances of classes being capable of being diffrent types of objects depending on ther instance used.

    Eg Animal is the parent class of the Person. Animal has a type assoisated with eg Mammal and a getter getType().
    Calling the getType on Person will treat that instance of person as type animal. 

3. What can we use to implement polymorphism in Java?

4. How many 'forms' can an object take when using polymorphism?

5. Give an example of when you could use polymorphism.
    Inheritance, Interfaces, 

 

# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
    Refering to a has-a realtionship and is directly constructed in the Class that requires it (ownership of it).
7. When would you use composition? Provide a simple example in Java.
    Car class which requires a Engine class for its construction. 
    
    public Car(){
        this.engine = new Engine()
    }


8. Give a difference between composition and aggregation?
    Both represents a has-a realtion ship but composition suggests a direct ownership and aggregation implies a strong link.



9. What is/are the advantage(s) of using composition/aggregation?
    Requires less inheritence, most cases a has-a realtionship is more accurate than a is-a realtionship.
    You can change the implmentation of a class during run time with composition and aggregation.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
All objects it is composed of are destoyed as they are no longer refernced anywhere
11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
Inverse because they are still referenced somewhere they remain. 