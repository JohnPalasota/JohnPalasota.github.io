---
layout: post
title: Grasp Principles
---

### 1. Creator
Shows which class should be responsible for creating objects/instances of a class.

### 2. Information Expert
Essentially the Single Responsibility Principle. It doesn't let objects get too bit or confusing. 
Answers the question of "Which object should have needed behavior?"

### 3. Low Coupling
Creates a pattern where your elements have less dependency so that:
- there are lower dependencies between classes
- changes in one class has a lower impact on other classes
- it has a higher reuse potential

### 4. High Cohesion
Keeps similar and related things together that share content, functionality, reason or goal

### 5. Controller
Non-user interface object that delegates work that needs to to be done to other objects. 

### 6. Indirection
Helps to ensure that coupling stays low. This breaks up chunks of work and has delegated pieces to deal with each chunk of the work.

### 7. Polymorphism
Helps to handle behavior based on type without the use of an if statement. Instead, you can use an overriden method from a super class or from implementing an interface.

### 8. Protected Variations
Addresses the problem of assigning responsibilities where as variations that occur do not have undesired effects on other elements in the system. It protects how objects can change.

### 9. Pure Fabrication
Helps to maintain Low Coupling and High Cohesion by assigning sets of highly cohesive responsibilities to a made up class.
An example of this would be a class that is solely responsible for saving objects instead of having data being saved in a different class along with other methods.
Doing this will increase reusability 
