# Relationships

A **relationship type R** among n entity types **E1, E2, . . . , En** defines a set of associations—or **a relationship set**—among entities from these entity types.

Mathematically, the relationship set **R** is a set of relationship instances **ri** , where each ri associates n individual entities **(e1 , e2 , . . . , en )**, and each entity **ej** in **ri** is a member of entity set **Ej, 1 ≤ j ≤ n**.

Hence, a relationship set is **a mathematical relation on E1, E2, . . . , En**; alternatively, it can be defined as a subset of the Cartesian product of the entity sets **E1 × E2 × . . . × En**.

Each of the entity types **E1, E2, . . . , En** is said to **participate in the relationship** type R; similarly, each of the individual entities **e1, e2 , . . . , en** is said to participate in the relationship instance **ri = (e1, e2, . . . , en)**.

---
### Degree of a Relationship Type
Degree of a relationship type is the number of participating entity types.
A relationship type of degree two is called binary, and one of degree three is called ternary.

---
### Role Names
Each entity type that participates in a relationship type plays a particular role in the relationship, and it helps to explain what the relationship means.

The **role name** signifies the role that a participating entity from the entity type plays in each relationship instance.

Eg. In **WORKS_FOR** relationship, **EMPLOYEE** plays the role of employee or worker and **DEPARTMENT** plays the role of department or employer.

Role names are not technically necessary in relationship types where all the participating entity types are distinct, since each participating entity type name can be used as the role name.

---
### Recursive Relationships
In some cases the same entity type participates more than once in a relationship type in different roles.

In such cases the role name becomes essential for distinguishing the meaning of the role that each participating entity plays.
Such relationship types are called **recursive relationships** or **self-referencing relationships**.

---
### Attributes of Relationship Types
Relationship types can also have attributes, similar to entity types.

For example, to record the number of hours per week that a particular employee works on a particular project, we can include an attribute **Hours** for the **WORKS_ON** relationship type.

