# Blood-Bank-Management-System



# Introduction

The BLOOD BANK MANAGEMENT SYSTEM is designed for successful the basic building aim is to provide blood donation service to the city recently. This project aims at maintaining all the information pertaining to blood donors, different blood groups available in each blood bank and help them manage in a better way.
The Blood Bank Management System (BBMS) is an application that stores, processes, retrieves, and analyzes data about blood bank administration. It also supervises blood inventory management and other blood bank-related activities. 
The major goal of the blood bank management system is to keep track of blood, donors, blood groups, blood banks, and stock information. It keeps track of all information concerning blood, blood cells, stocks, and blood. Because the project is all done at the administrative level, only the administrator can see it.

Normalization is a technique of organizing the data in the database. Normalization is a systematic approach of decomposing tables to eliminate data redundancy(repetition) and undesirable characteristics like Insertion, Update and 
Deletion Anomalies. It is a multi-step process that puts data into tabular form, removing duplicated data from the relation tables. Normalization is used for mainly two purposes,
• Eliminating redundant(useless) data.
• Ensuring data dependencies make sense i.e data is logically stored


Problems Without Normalization
If a table is not properly normalized and have data redundancy then it will not only 
eat up extra memory space but will also make it difficult to handle and update the 
database, without facing data loss. Insertion, Updation and Deletion Anomalies are 
very frequent if database is not normalized. To understand these anomalies let us
take an example of a Student table.

First Normal Form (1NF)
For a table to be in the First Normal Form, it should follow the following 4 rules:
1. It should only have single(atomic) valued attributes/columns.
2. Values stored in a column should be of the same domain
3. All the columns in a table should have unique names.
4. And the order in which data is stored, does not matter.



Second Normal Form (2NF)
For a table to be in the Second Normal Form,
1. It should be in the First Normal form.
2. And, it should not have Partial Dependency.



Third Normal Form (3NF)
A table is said to be in the Third Normal Form when,
1. It is in the Second Normal form.
2. And, it doesn't have Transitive Dependency.


Boyce and Codd Normal Form (BCNF)
Boyce and Codd Normal Form is a higher version of the Third Normal form. This 
form deals with certain type of anomaly that is not handled by 3NF. A 3NF table 
which does not have multiple overlapping candidate keys is said to be in BCNF. For a 
table to be in BCNF, following conditions must be satisfied:
1. R must be in 3rd Normal Form
2. and, for each functional dependency ( X → Y ), X should be a super Key
