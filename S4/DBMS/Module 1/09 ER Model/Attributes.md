# Attributes

In general, an attribute is **a property or characteristic** **of an entity**. An entity may contain any number of attributes. 
One of the attributes is considered as the primary key. In an Entity-Relation model, attributes are represented in an elliptical shape. 
Example: Student has attributes like name, age, roll number, and many more.


Attributes can be classified based on different criterions :

## Simple and Composite Attributes

| Simple Attribute                    | Composite Attributes                   |
| ----------------------------------- | -------------------------------------- |
| Cannot be divided further           | Can be divided Further                 |
| Cannot forma hierarchy              | Can form a hierarchy                   |
| Formed with only a single attribute | Consists of multiple simple attributes |
| Eg :- Ssn | Eg :- the Address attribute can be divided into multiple simple attributes |
![[composite attribute hiearchy.png]]

## Single-Valued and Multivalued Attributes

| Single-Valued                                                       | Multivalued                                  |
| ------------------------------------------------------------------- | -------------------------------------------- |
| a single value for a particular entity                              | a set of values for the same entity          |
| No upper bounds or lower bounds unless specifies in the constraints | may have lower and upper bounds to constrain |
| For example, Age is a single-valued attribute of a person.          | College_degrees attribute for a person.      |

## Stored and Derived Attributes

In some cases, two (or more) attribute values are related—for example, the Age and Birth_date attributes of a person.

For a particular person entity, the value of Age can be determined from the current (today’s) date and the value of that person’s Birth_date .

The Age attribute is hence called a **derived attribute** and is said to be derivable from the Birth_date attribute, which is called a **stored attribute**.

Some attribute values can be derived from related entities; for example, an attribute Number_of_employees of a DEPARTMENT entity can be derived by counting the number of employees related to (working for) that department.

## Complex Attributes

Notice that, in general, composite and multivalued attributes can be nested arbitrarily.
We can represent arbitrary nesting by grouping components of a composite attribute between parentheses ( ) and separating the components with commas, and by displaying multivalued attributes between braces { }.

Such attributes are called **complex attributes**.

Eg :- Address (Street_address (Number, Street, Apartment_number), City, State, Zip) )}

## Null Values

In some cases, a particular entity may not have an applicable value for an attribute. for eg, A College_degrees attribute applies only to people with college degrees.
For such situations, a special value called NULL is created.

NULL can also be used if we do not know the value of an attribute for a particular entity—for eg, if we do not know the home phone number of a person.

The meaning of the former type of NULL is **not applicable**, whereas the meaning of the latter is **unknown**.

## Value Sets (Domains) of Attributes

Each simple attribute of an entity type is associated with a value set (or domain of values), which specifies the set of values that may be assigned to that attribute for each individual entity.

If the range of ages allowed for employees is between 16 and 70, we can specify the value set of the Age attribute of EMPLOYEE to be the set of integer numbers between 16 and 70.

Similarly, the value set for the Name attribute can be the set of strings of alphabetic characters separated by blank characters, and so on.

Value sets are not typically displayed in basic ER diagrams and are similar to the basic data types available in most programming languages, such as integer, string, Boolean, float, enumerated type, and so on.

