# Self Describing Nature
The database system contains not only the database itself but also a complete
definition or description of the database structure and constraints.

This definition is stored in the DBMS catalog, which contains information such
as the structure of each file, the type and storage format of each data item, and
various constraints on the data.

A general-purpose DBMS software package is not written for a specific
database application, it refers to the catalog to know the structure of the files in
a specific database, such as the type and format of data it will access.

In traditional file processing, data definition is typically part of the application
programs themselves. Hence, these programs are constrained to work with only
one specific database, whose structure is declared in the application programs.

#### Example Database
![[A student DB.png]]

#### Data Catalog
![[DB Catalog.png]]

#### Internal Storage Format
![[Internal Storage format.png]]

