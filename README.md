# Database development project (Microsoft Access)
### Project overview

-	We need to develop a simple database for a local library
-	An ER diagram should be designed showing the tables and the relationships between them
-	The tables and their relationships should be created either with SQL queries or manually from the MS Access environment
-	For testing purposes, we should add at least 4 entries in each table, one form and one report for at least one table
-	Multiple client questions are being answered by SQL queries

### Table relationships

-	We have six tables: Members, Authors, Books, Categories, Borrowings, Authors_Books 
-	The table “Members” is associated with the table “books” in a many-to-many relationship (N/M) creating a new table called “Borrowings”.
-	The table “Authors” is associated with the table “books” in a many-to-many relationship (N/M) creating a new table called “Authors_Books”.
-	The table “Categories” is associated with the table “books” in a one-to-many relationship (1/N)
 
### ER diagram

![ER diagram](/images/ER_diagram.png?raw=true)

### Relationships design
The relational diagram as presented by MS access:

![ralational_diagram](/images/Relational_diagram.png?raw=true)

### Tables
The table Books followed by the SQL query which was used for its creation:

![books_table](/images/books_table.png?raw=true)

SQL query:
![books_table_create](/images/books_table_create.png?raw=true)

### Forms
The author’s form:  

![form](/images/Form.png?raw=true)

### SQL Queries

Display the details of the members who have borrowed a book on "11/2/2022".

-1st solution

![Query_1st](/images/Query_1st.png?raw=true)

-2nd solution

![Query_2nd](/images/Query_2nd.png?raw=true)

