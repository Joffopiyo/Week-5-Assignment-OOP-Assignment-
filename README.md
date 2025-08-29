# Week-5-Assignment-OOP-Assignment-
Superhero and Polymorphism

-- OOP Assignment: Superhero and Polymorphism
This project contains a single Python script, superhero.py, which fulfills two object-oriented programming (OOP) assignments. The script demonstrates key OOP principles, including class design, inheritance, and polymorphism.

Assignment 1: Design Your Own Class
This section of the code designs a Superhero class and a Vigilante subclass to demonstrate core OOP concepts:

Classes and Objects: The Superhero class defines a blueprint with attributes (name, superpower, weakness) and methods (fly(), land(), display_status()). The Vigilante class demonstrates inheritance by extending the Superhero class and adding its own unique attribute (gadget) and method (use_gadget()).

Constructors (__init__): The constructors for both classes are used to initialize objects with unique values, as seen in the creation of superman and batman objects.

Encapsulation: The private attribute _is_flying is used within the Superhero class to control access to its internal state, a form of encapsulation.

Activity 2: Polymorphism Challenge
This section demonstrates polymorphism by creating several different vehicle classes (Car, Plane, Submarine, Bicycle), each with a unique implementation of a shared method: move().

Polymorphism: The perform_move() function can accept any of the vehicle objects. It calls the move() method on the object, and because of polymorphism, the correct method for that specific object is executed, resulting in a different output for each vehicle. This showcases how the same method call can behave differently depending on the object it's called on.

How to Run
To run the script, simply execute the file using a Python interpreter from your terminal:

python superhero.py

The output will display the status of the superhero and vigilante objects, followed by the polymorphic output from the different vehicle
