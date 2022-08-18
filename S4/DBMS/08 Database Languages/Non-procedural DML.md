# Non-procedural DML

A **high-level or nonprocedural DML**, such as [[SQL]], can specify and retrieve many records in a single DML statement; therefore, they are called **set-at-a-time or set-oriented DMLs**.

Many DBMSs allow high-level DML statements either to be entered interactively from a display monitor or terminal or to be embedded in a general-purpose programming language.

In the latter case, DML statements must be identified within the program so that they can be extracted by a precompiler and processed by DBMS.

A query in a high-level DML often specifies which data to retrieve rather than how to retrieve it; therefore, such languages are also called **declarative**.

Whenever DML commands, whether high level or low level, are embedded in a general-purpose programming language, that language is called the **host language** and the DML is called the **data sublanguage**.

On the other hand, a high-level DML used in a standalone interactive manner is called a **query language**. 

Casual end users typically use a high-level query language to specify their requests, whereas programmers use the DML in its embedded form.
For naive and parametric users, there usually are **user-friendly interfaces** for interacting with the database; these can also be used by casual users or others who do not want to learn the details of a high-level query language.


