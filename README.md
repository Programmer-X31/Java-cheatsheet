  
# Java Notes

## Contents:  
1. [Basic Knowledge](#basic-knowledge)
1. [OOP](#oop)  
3. [Classes in Java](#classes-in-java)  
5. [Data Types](#data-types)  
6. [Data Casting](#data-casting)  
7. [Polymorphism Concepts](#polymorphism-concepts)  
8. [Basic Polymorphism in Java](#basic-polymorphism-in-java)  
9. [Interfaces and abstraction](#interfaces-and-abstraction)
10. [Garbage Collection](#garbage-collection)

## Basic Knowledge
Java is a Object-Oriented Programming Language. This means that Java is written based on classes and not on functions or procedures like in C.
It is a compiled language, meaning that it requires a compiler which you can download from https://www.oracle.com/in/java/technologies/javase-downloads.html. 


### Writing your program


### Running your Program
While compilation, each class is compiled into a new file with `.class` extension. The Java interpreter searches and runs the main method (called main) within the file you inputted. Other methods shall be accessed only through main.  

Code is written in a `.java` file which is compiled by the compiler using the command  
```
javac YourProgramName.java
```
This gives a new file with the same name but with a `.class` extension. You can run this by:  
```
java YourProgramName
```
_**Make sure that the .class extension is not included in the command above**_  

If not:
``` sh
$ java YourProgramName.class
Error: Could not find or load main class Hello.class
```
The `.class` file is read by interpreter which executes it. 

**When a `.class` file with no main method is run**
```
$ java MyProgramWithNoMainMethod
Error: Main method not found in class Hello, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application
```

**A class with a main method**  
```java 
public class Program {
	public void main(String[] args) {
		// Your code here
	}
}
```
## OOP
