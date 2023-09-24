# Event System !

### This is a Spring Boot project and H2 database, which implements the following conceptual model:
&nbsp;

![](images/event-system-model.jpg)

The objective of the system is to manage the information of participants in the activities of a
academic event. The activities of this event can be, for example, lectures, courses, workshops
practices, etc. Each activity that takes place has a name, description, price, and can be divided into several blocks of time (for example: an HTML course can take place in two blocks, requiring
store the day and the start and end times of that day's block). For each participant, you want to register your name and email.

&nbsp;
### Through the bank seed, participants, activities, categories and time blocks are added:
&nbsp;

![](images/seed.png)
&nbsp; 
&nbsp; 

### H2 database:

![](images/h2.png)
&nbsp; 
&nbsp; 


To create this system, the following were done:

- Implementation of domain entities

- Object-relational mapping with JPA

- Spring Boot project setup for H2 database

- H2 database seeding
&nbsp;

&nbsp;
&nbsp;
Use ORM, or Object-Relational Mapping, simplifies the experience of interacting with a database, bridging the gap between the object-oriented programming world and the relational database world. This is done through the following mechanisms:

- Abstraction of database operations
- Mapping between objects and tables
- Automatic SQL generation

         
&nbsp;
 ![](images/system.png)

&nbsp; 
&nbsp; 


As you can see, the data was correctly generated in the database and the Domain Model was successfully implemented.
