# juliarDocs2

Juilar is an fun, easy to learn, powerful programming language. It was initially written in javascript. The main aim to provide programming language that is that anyone can grasp easily and get to real world coding. Juliar combines the features functional languages such as lisp with imperative languages like Java.
Juliar Future is Latest interation of Juliar programming language . It runs directly over the Java Virtual machine(JVM). That means juliar can run on almost any computer that java can run on. Getting started with the language is quite easy, just follow few pages and you are good to go.

# Getting started with juliar

### Prequisites

 - Java devlopment Kit (JDK) can be downloaded from here -http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
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
 
 Inorder to add number we have to write in infix notation
 Meaning to perform `5 + 3` we have to write it as `+ 5 3`
 Example -
 ``` 
 function main()= {
         int a = + 3 4;
	 printLine(a);
}
```

# Executing Codes via Command Line

you can execute juliar code by command line without using the Build-in IDE. 
1. Open up a text editor. 
2. Write the juliar code. Save the file is ``something.jrl``
3. Open the command prompt in the same Directory/folder by right clicking on the Folder.
4. Write the following in the command prompt
  ```
  java -jar JuliarCompiler.jar something.jrl
  ```
 
 


  

