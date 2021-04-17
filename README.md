  
# Java Notes

## Contents:  
1. [Basic Knowledge](#basic-knowledge)
1. [OOP](#oop)  
3. [Classes in Java](#classes-in-java)  
4. [Basic I/O Methods](#basic-i/o-methods)  
5. [Data Types](#data-types)  
6. [Data Casting](#data-casting)  
7. [Polymorphism Concepts](#polymorphism-concepts)  
8. [Basic Polymorphism in Java](#basic-polymorphism-in-java)  
9. [Interfaces and abstraction](#interfaces-and-abstraction)
10. [Garbage Collection](#garbage-collection)

## Basic Knowledge
Java is a Object-Oriented Programming Language. This means that Java is written based on classes and not on functions or procedures like in C.
It is a compiled language, meaning that it requires a compiler which you can download from https://www.oracle.com/in/java/technologies/javase-downloads.html. 

### Running your Program
Code is written in a ```.java ``` file which is compiled by the compiler using the command 
```sh 
javac YourProgramName.java
```
This gives a new file with the same name but with a ```.class``` extension. You can run this by:
```sh 
java YourProgramName
```
_**Make sure that the .class extension is not included in the command above**_  

The ```.class``` file is read by interpreter which executes it.  

### Writing your program
While compilation, each class is comiled into a new file with ```.class``` extension. The java interpreter searches for the main method (called main) which it runs at first. Other methods shall be accessed only through main.

**A class with a main method**  
```java 
public class Program {
	public void main(String[] args) {
		// Your code here
	}
}
```
## OOP
