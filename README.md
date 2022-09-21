# VaibhavKoshta_Spring_MVCLabSolution

In this repository, spring and hibernate is implemented using javaee.

**Problem statement**
In College fest, Students want to take registrations for a Debate event and want to keep track of 
student details based on the department. Help the students to create a table with the help of 
Spring, MVC, Hibernate ORM to perform CRUD operations on the table.

**Explaination**
A web.xml file is created which is used to configure the MVC dispatcher servlet.

A servlet file is created which is used to create the view resolver, session factory and hibernate properties. It is also used to give the path of MySQL database to store the data.

Student class contains all the respective annotations to create a table along with getters and setters and overriding toString method. The StudentController class is created for performing the CRUD (create, read, update and delete) operation in the student form.
