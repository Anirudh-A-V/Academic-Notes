# Physical Data Independence

It is the capacity to change the **internal schema** without having to change the **conceptual schema**.

Hence, the external schemas need not be changed as well.

Changes to the internal schema may be needed because some physical files were reorganized—for example, by creating additional access structures—to improve the performance of retrieval or update.

If the same data as before remains in the database, we should not have to change the conceptual schema.

Generally, physical data independence exists in most databases and is easy to achieve, where, logical data independence is harder to achieve.