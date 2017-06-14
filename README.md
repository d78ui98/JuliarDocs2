# juliarDocs2

Juilar is an fun, easy to learn, powerful programming language. It was initially written in javascript. The main aim to provide programming language that is that anyone can grasp easily and get to real world coding. Juliar combines the features functional languages such as lisp with imperative languages like Java.
Juliar Future is Latest interation of Juliar programming language . It runs directly over the Java Virtual machine(JVM). That means juliar can run on almost any computer that java can run on. Getting started with the language is quite easy, just follow few pages and you are good to go.

# Getting started with juliar

### Prequisites

 - Java Runtime Environment (JRE) can be downloaded from here -http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html
 - JuliarCompiler.jar file can be downloaded from here - https://juliar.org/downloads.php

# Initial Programs
 ### Hello world
 
 Click on the JuliarCompiler.jar after installing the Java devlopment kit. 
 This will directly start the juliar build-in IDE
 ```
function main()= {
	printLine("Hello World");
}
 ```
 Inorder to run directly click on the play button or go to Run > Run Interpreter
 
 ### Addition of 2 numbers
 
 Inorder to add number we have to write in prefix notation
 Meaning to perform `5 + 3` we have to write it as `+ 5 3`
 Example -
 ``` 
 function main()= {
         int a = + 3 4;
	 int b = + 2 4 2 3;
	 printLine(a);
	 printLine(b);
}
```

# Executing Codes via Command Line

you can execute juliar code by command line without using the Build-in IDE. 
1. Open up a text editor. 
2. Write the juliar code. Save the file is **something.jrl**
3. Open the command prompt in the same Directory/folder by right clicking on the Folder.
4. Write the following in the command prompt
  ```
  java -jar JuliarCompiler.jar something.jrl
  ```
  
# Basic Programming Syntax

### 1.Comments
 Comments can be added by using \/\* opening and for closing \*\/
### 2. Data Types
 Currently Juliar supports int, float, double, string, boolean
### 3. Printing on screen
 In juliar we have `print` `printLine` for displaying stuff on the screen. 
 ```
 print - it is used to display text
 printLine - it is used to display text and move curson to next line.
```
### 3. Functions
 Writing function in juliar is pretty straightfoward. You have to use the keyword function followed by the name of the function then an assignment operator(=) followed by opening and closing brackets. Here = sign copies the data of the stuff into a callable function.
 main function acts as in entry point
 ```
 function main()= {
	 int a = + 3 6;
       print(a);
 ```
 ### 4. Classes
 Juliar uses concept of classes to Encapsulate functions of similar type.Basic syntax of class is 
 ```
 class asdf ={
       Somecode();
 }
 ```
 ### 5. Loops
 Loops are basically used to run a piece of code multiple time. Loops have a terminating condition. Basic syntax for while loop is-
 ```
  function main()={
     int x = 0;
     while(true) {
     x = + x 1;
     if(x==4){break;}
     printLine(x);
}
}
 ```
### 
