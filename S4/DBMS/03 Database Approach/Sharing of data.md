# Sharing of Data and Multiuser Transaction Processing

A multiuser DBMS, as its name implies, must allow multiple users to
access the database at the same time.

This is essential if data for multiple applications is to be integrated and
maintained in a single database.

The DBMS must include concurrency control software to ensure that
several users trying to update the same data do so in a controlled manner
so that the result of the updates is correct.
Eg: Just like how **git** does with version control

Or, when several reservation agents try to assign a seat on an airline flight,
the DBMS should ensure that each seat can be accessed byonly one agent 
at a time for assignment to a passenger.

These types of applications are generally called **online transaction processing ([[OLTP]])** applications.

A fundamental role of multiuser DBMS software is to ensure that
concurrent transactions operate correctly and efficiently.