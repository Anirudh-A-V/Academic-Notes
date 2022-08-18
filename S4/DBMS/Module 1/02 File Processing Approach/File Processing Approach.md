# File processing approach

###### **[[Redundancy]]**
<i>In engineering</i>
		the inclusion of extra components which are not strictly necessary to functioning, in case of failure in other components:

"a high degree of redundancy is built into the machinery installation"

In traditional file processing, each user defines and implements the files needed
for a specific software application as part of programming the application.

For example, one user, the **grade reporting office**, may keep files on students and their grades. A second user, the **accounting office**, may keep track of students’ fees and their payments.
Although both users are interested in data about students, each user maintains separate files—and programs to manipulate these files—because each requires some data not available from the other user’s files.

This redundancy in defining and storing data results in wasted storage space and in redundant efforts to maintain common up-to-date data.

In the [[Database Approach]], a single repository maintains data that is defined once and then accessed by various users repeatedly through queries, transactions, and application programs.