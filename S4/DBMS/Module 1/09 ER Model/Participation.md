# Participation Constraints and Existence Dependencies

The **participation constraint** specifies whether the existence of an entity **depends on its being** related to another entity via the relationship type.

It specifies the min. no. of relationship instances that each entity can participate and is sometimes called **minimum cardinality constraint**.

There are two types of participation constraints—
			- Partial
			- Total

If a company policy states that every employee must work for a department, then an employee entity can exist only if it participates in at least one WORKS_FOR relationship instance.

Thus, the participation of EMPLOYEE in WORKS_FOR is called total participation, meaning that every entity in the total set of employee entities must be related to a department entity via WORKS_FOR.

Total participation is also called **existence dependency**.

## Participation Constraint - Partial

Every employee is not expected to manage a department, so the participation of EMPLOYEE in MANAGES relationship type is **partial**,
		- meaning that some or part of the set of employee entities are related to some department entity via MANAGES , but not necessarily all.

We will refer to the cardinality ratio and participation constraints, taken together, as the **structural constraints** of a relationship type.

