# TOPTAL Calculator


## Introduction

This project is part4 of the [interview](http://www.toptal.com/top-3-percent) for joining [Toptal](www.toptal.com).


## Specification

Text of the task is given in the file **task.txt**


## Technology

Calculator is implemented in Scala programming language. ScalaFX library was used for Calculator's
 GUI implementation and sbt for project building.
   
   
## Requirements

* Java 8
* ScalaFX 8 
* Scala 2.11
* sbt 0.13.8


## Run calculator

Enter the project  folder and type:

 ```
 sbt run
 ```
 
 
## Tests
 
 Tests are located in folder **/src/test/scala-2.11**,  For running all tests enter the project folder and type:
 
 ```
 sbt test
 ```
 
## Library dependencies

* scalatest - test driven development
* scalafx - modern library for GUI
* scala-logging - for logging

More details about project libraraies (e.g. version etc..) can be found in file **build.sbt**


## Logs

Logs are located in **logs** folder.  Log settings are located in **resources/logback.xml**


## ScalaDocs

ScalaDocs can be generated by entering project folder and typing:

```
sbt doc
```

ScalaDoc will be generated in folder **scalaDoc**.  Open file **index.html** in browser in order to start 
browsing projects documentation


## Using a calculator

After running calculator will show up in the center of the screen as shown on the next image:


![Image of Calculator](https://github.com/milosjava/codilityScala/blob/master/images/calculator.png)


### Buttons

Here's the list of the available buttons: 

*    ![0](images/zero.png?raw=true "zero")) &nbsp;&nbsp;&nbsp;  to &nbsp;&nbsp;&nbsp; ![9](images/nine.png)  are numbers 
*    ![linear](images/linear.png) &nbsp;&nbsp;&nbsp; are used for linear equation
*    ![clear](images/clear.png) &nbsp;&nbsp;&nbsp;  clear, delete all
*    ![binary](images/binaryOperations.png) &nbsp;&nbsp;&nbsp;  operations
*    ![log](images/log.png) &nbsp;&nbsp;&nbsp;  logarithm
*    ![brackets](images/brackets.png)&nbsp;&nbsp;&nbsp;  brackets
*    ![point](images/point.png)&nbsp;&nbsp;&nbsp;  point for floating point numbers
*    ![calculate](images/calculate.png)&nbsp;&nbsp;&nbsp;  calculate!










 
 
 
 


