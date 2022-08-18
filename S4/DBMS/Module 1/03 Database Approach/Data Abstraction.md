# Insulation between Programs and Data, and Data Abstraction

**Data abstraction** generally refers to the suppression of details of data organization and storage, and the highlighting of the essential features for an improved understanding of data.

In traditional file processing, the structure of data files is embedded in the application programs, so any changes to the structure of a file may require changing all programs that access that file.

By contrast in DBMS, the structure of data files is stored in the **DBMS catalog** separately from the access programs.

This property is called **program-data independence**, and the characteristic that allows it is called **Data Abstraction**.

A DBMS provides users with a conceptual representation of data that does not include many of the details of how the data is stored.

Informally, a **[[Data Model]]** is a type of data abstraction that is used to provide this conceptual representation.