# Clases and Objects

## Object-oriented programming (OOP)
- Involves programming using objects.
- An object represents an entity/object in the real world.
- An object has a state, a behavior, and an identity.

Example:
- Student, circle, button, bank account,...
- To represent a real world point in programming we create a Point Object.

### The state (properties/attribute) of an object
Represented by the data fields of the object with their current value.

A point object, for example, has a data field x and y that characterizes a point.

A rectangle object, for example, has the data fields height and width, that characterizes a rectangle.

### The behavior of an object
defined by the methods of an object
- The behavior of an object is also known as its actions.
- To invoke/call a method on an object is to ask the object to perform an action.

### The identity of an object
What makes an object unique
```
Point p1 = new Point(0, 1);
Point p2 = new Point(0, 1);

System.out.println(p1 == p2); // false becuase the adress of p1 is different from p2
```
