# Logical Data Independence

It is the capacity to change the **conceptual schema** without having to change **external schemas** or application programs.

We may change the conceptual schema to expand the database (by adding a record type or data item), to change constraints, or to reduce the database (by removing a record type or data item).

In the these cases, external schemas that refer only to the remaining data should not be affected.

After the conceptual schema undergoes a logical reorganization, application programs that reference the external schema constructs must work as before.

Changes to constraints can be applied to the conceptual schema without affecting the external schemas or application programs.

