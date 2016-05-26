# HelloWorldSpringMavenWebApp

This is the sample spring web applications which has one api which returns HelloWorld json response.

Project Include features like

Spring : Spring framework is an open source Java platform that provides comprehensive infrastructure support for developing robust Java applications very easily and very rapidly.

Maven : Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

To get the code:

Clone the repository:

https://github.com/TejaVaranasi/HelloWorldSpringMavenWebApp.git


To run the application:

mvn clean compile package

place war package created under /target directory and move that package into tomcat's webapps directory

try running this app through http://localhost:8080/

then you can see the proper json response with message "Hello World"
