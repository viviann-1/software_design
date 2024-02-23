### Software Design Methodologies

1. Question 1 What do we mean by coupling and cohesion when discussing structured design?

Coupling indicates that software modules can have a level of interdependence. Coupling can be high or low, with high meaning the modules are closely linked and so a change in one can lead to a change in the others, whereas low is the opposite, thus a change in one will not lead to a change in the others - and so they are independent.

Cohesion occurs when parts or elements within a module work well together in order to fulfil a single task/ purpose. Cohesion can also be high or low, with high meaning each element is closeley focused/ connected in order to fulfil the purpose, whereas low indicates that the elements within the modules don't work so closely and can fulfil multiples tasks/ purposes.


2. Question 2 What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

In oriented design, top-down design refers to creating the overall structure first, and then going back and dividing it into smaller and smaller parts, where further detail can be added. You are essentially 'refactoring' when breaking parts down into smaller pieces or 'dividing and conquering'.

In oriented design bottom-up design refers to creating the individual and smaller/ specific elements first. These parts are then joined together to start creating the 'bigger picture' and are all linked until a complete system is created.

A function oriented design could be best described as top-down.


3. Question 3 In which design methodology would a class diagram be most useful?

A class diagram would be most useful for an object oriented design methodology.


4. Question 4 What are the four pillars of object oriented programming? Give a single-sentence description of each.

The 4 pillars of object oriented programming are:

- Abstraction - Only showing the details that are necessary to the user and hiding the rest - using abstract classes and interfaces.

- Encapsulation - wrapping attributes into a class for example and making them private, and using getters and setters to access it.

- Inheritance - Where a parent class/ super-class can pass on its properties to a child-class/ sub-class.

- Polymorphism - Allows a sub-class to have its own unique behaviours whilst inheriting attributes and methods from the super-class - so allows us to perform a single action in different way.



5. Question 5 What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

Strategy Pattern is a method that allows you to create and encapsulate classes/ strategies that can be called on interchangeably at runtime from the client side, and which you can assign different responsibilities to.

When implementing the strategy pattern on a functional object oriented system you would solely use functions to implement the strategy thanks to high order functions where one function can take on another functions parameters.

When implementing the strategy pattern on an object oriented system you would create a class that will delegate responsibility to various objects/ strategies, ensuring to programme to the interface and implement the single responsibility principle.


6. Question 6 Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

The methodology I would suggest would be object oriented as it abides by the "open for extension - closed for modification principle" which means you can write new code without having to change the existing code. This also means single responsibility is applied so if and when you create a change in one class, it will not affect another class. Thus, this will make it easier to adapt the code to fit the particular sector its needed in. The code will be easy to test and maintain whilst still being adaptable in the furture to fit new requirement.