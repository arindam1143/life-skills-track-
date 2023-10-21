### Object-Oriented Programming (OOP) 

**Introduction**
In this technical report, we will delve into Object-Oriented Programming (OOP) concepts and their application in code refactoring. Codebase maintenance and improvement are crucial for project sustainability and efficiency. This report aims to provide insights into the principles of OOP and offer practical code samples to demonstrate the benefits of refactoring.

### Object-Oriented Programming (OOP)
OOP is a programming paradigm that promotes code organization around objects, which are instances of classes. 

###What are the benefits of Object Oriented Programming
**1.**Higher quality software
**2.**Faster development sprints
**3.**Lower cost of development
**4.**Improved software maintainability

**Encapsulation:** Encapsulation ensures data hiding and provides a clear interface to interact with objects. Example in Java:


public class Employee {
    private String name;
    private double salary;

    public void setName(String name) {
        this.name = name;
    }

    public String getName() {
        return name;
    }
}

 **Inheritance:** Inheritance allows for code reuse and the creation of a hierarchy of classes. Example in Java:


public class Manager extends Employee {
    // Manager-specific attributes and methods
}
Polymorphism: Polymorphism enables the use of different classes in a unified way. Example in Java using method overriding:


public class Circle {
    public double calculateArea() {
        // Calculate area of a circle
    }
}

public class Square {
    public double calculateArea() {
        // Calculate area of a square
    }
}
### Code Refactoring
Code refactoring is the process of restructuring existing code to improve readability, maintainability, and performance without altering its external behavior. Key refactoring techniques include:

 **Extract Method:** Splitting complex methods into smaller, more focused methods for improved readability.
**Extract Class:** Creating new classes to encapsulate related functionality and avoid class bloat.
**Inheritance to Composition:** Replacing deep class hierarchies with composition, enhancing flexibility.
**Rename Variables and Methods:** Using descriptive names to enhance code readability.
**Remove Duplicate Code:** Identifying and eliminating repeated code segments for efficiency.

###Conclusion
Understanding OOP concepts and applying code refactoring techniques is essential for managing complex codebases. It leads to cleaner, more maintainable code that helps teams work more efficiently and reduce the risk of bugs and errors.


