

Intro:
The following review is about milestone 2 procedure development and involves turning the crud analysis into workable procedures for a database u
sing the crud table as a reference for which objects should be interacted with in the database.

Project thoughts:
The process of creating these functions from the initial design and CRUD to real SQL involved creating the required functions and 
then putting them inside procedures so the database works efficiently and reliably. Also each of these procedures had transactions to ensure
ACID (Atomicity, Consistency, Isolation, Durability) to provide isolation between different functions/procedures accessing the database
at the same time. If this isolation is not provided then the database's procedure outcomes can result in errors because if this.
At the end of creating each new function / procedure it was checked against the test data to make sure it was correct and could interact wit the data sets 
of the database.

With Milestone 2 I’ve found I prefer to MySQL to SQL server  this is because MySQL tends to be a nit more forgiving and less strict then its SQL server counter.
An example of this is that SQL server requires  of users that  current tabs that have a connection with the database must be changed before the database schema can be dropped.
This is not the case in MySQL where schemas can be altered and dropped with relative ease this came in handy when developing the different procedures
because it involved quite a lot of alterations to the procedure and to able to then run these procedures on the database it needed to be alerted or sometimes the scheme deleted/dropped entirely.
Helpful things:

Through out the procedure making progress it was very useful to keep referring to the MySQL dev documentation which detailed 
all of the syntax of MySQL and listed explanations of functions and examples of that implementation. This helped me a lot especially 
because working with different DBMS’s (Database management software) and all sorts of other code the specific syntax and way a function is 
created can easily be forgotten so this reference material was incredibly helpful for that.
