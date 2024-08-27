Documentation

I created a prompt system for the user to view the options and select actions in the student management system, because of this i have remade the original method StudentManagementSystem to have the prompt actions included.
I have the class Student Database directly handle most of the operations related to the database

The update method in the student class was moved to the Student Database class for better code management

KISS (Keep It Simple, Stupid)
The StudentManagementSystem class adds an extra layer of abstraction that might not be necessary for a simple student management application. It could be argued that directly using the Student Database class would suffice in many cases.

DRY (Don't Repeat Yourself)
We tried to remove as much of the repetitive actions the program was making, some functions in previous StudentManagementSystem class was offloaded to the other classes

SOLID 
the parts of the code would Ideally have some methods be handled by another method or class, but i tried to keep the code simple as the KISS principle
