# Cardinality Ratio

The cardinality ratio for a binary relationship specifies the maximum number of relationship instances that an entity can participate in.

For example, in the **WORKS_FOR** binary relationship type, **DEPARTMENT : EMPLOYEE** is of cardinality ratio **1:N**,
			- meaning that each department can be related to (that is, employs) any number of employees (N),
			- but an employee can be related to (work for) at most one department (1).
			- This means that for this particular relationship type **WORKS_FOR** , a particular department entity can be related to any number of employees (N indicates there is no maximum number).

The possible cardinality ratios for binary relationship types are **1:1**, **1:N**, **N:1**, and **M:N**.

### 1:1 Relationship Type

![[1 isto 1 relation.png]]


### M:N Relationship Types

![[fig7.13.png]]

