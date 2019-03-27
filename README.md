# Java Module 3: OOP Design

**Your Name** Patrick McCarthy
 - patrickjm@gwu.edu
 - patrickjm98

## Exercise 3.0: Answer Question 1 on the worksheet

## Exercise 3.1:
>Draw a UML diagram to represent the Mail System with both voice and text message support. Display the image in your Readme.

## Exercise 3.2:
>Draw a UML diagram to represent the Banking System. Display the image in your Readme.

## Exercise 3.3:
>List or draw out the memory contents for the seven slides (23-29) with `StaticExample` or `DynamicExampleXXX` and `ObjX` classes. You can either draw a picture with boxes and arrows for pointers (you do not need to show addresses), or you can clearly list out what memory is stored in each region (Stack, Heap, or Globals).  Assume the garbage collector has not yet run.

## Exercise 3.4:
>In what cases does polymorphism work correctly for the lines below? Explain why or why not for each line.
```java
1: Employee e0 = new Employee ("Gullible Gus", "555-55-5678", 50000);
2: Employee e1 = new Customer ("Gullible Gus", "555-55-5678", 5);
3: Employee e2 = new Person("Zany Zoe", "112-12-1212");
4: Person p1 = new Customer ("Gullible Gus", "555-55-5678", 5);
5: Person p2 = (Person) e0;
6: Customer c1 = (Person) p1;
7: Customer c2 = p1;
8: Person p3 = (Employee) e0;
9: Person p4 = e0; // note, in the original version of this page this said p3 = ...
```
