# Struts2-Project

## Introduction To MVC

MVC Pattern stands for Model-View-Controller Pattern. This pattern is used to separate application's concerns.  

###### Model
Model represents an object or JAVA POJO carrying data. It can also have logic to update controller if its data changes.

###### View
View represents the visualization of the data that model contains.  

###### Controller
Controller acts on both model and view. It controls the data flow into model object and updates the view whenever data changes. It keeps view and model separate.

###### Popular Java Web MVC Frameworks

1. Struts
2. Struts 2
3. Spring MVC
4. JSF
5. Play
6. Wicket


## Introduction To Struts 2

The struts 2 framework is used to develop MVC-based web application.  
  
The Struts 2 framework is used to develop MVC (Model View Controller) based web applications. Struts 2 is the combination of webwork framework of opensymphony and struts 1.  
  
The Struts 2 provides supports to POJO based actions, Validation Support, AJAX Support, Integration support to various frameworks such as Hibernate, Spring, Tiles etc, support to various result types such as Freemarker, Velocity, JSP etc.


## Setting Up

###### Download Struts 2
Link: https://struts.apache.org/

###### Create Project

*Install server like Apache if not already installed
Link: https://github.com/dileepdail/Servlet-And-JSP-Projects#configure-tomcat-in-eclipse

1. Click new Project
2. Enter Dynamic Web Project
3. Click next, next
4. Change Content directory to web
5. Check generate web.xml
6. Add custom user library for Struts JARs
    * Click right click on project
    * Select properties
    * Select Java Build Path
    * Click on Libraries TAB from top
    * Select Add libraries on right
    * Select User library from list
    * Click new 
    * Enter name. Eg. Struts2
    * Add JARS from dwonload folder from Struts website. Can select all
    * Apply and close all
7. Link this new library in default lib folder
    * Click right click on project
    * Select properties
    * Select Deployment Assembly
    * Click Add on the right
    * Select Java Build Path Entries
    * Select the library i.e. Struts2
    * Finish

