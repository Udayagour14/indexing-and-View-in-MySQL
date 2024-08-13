# SQL revision day 8
Day 8 of my 15-day SQL revision journey with MySQL! 🎉 Even with my experience in SQL, I'm excited to revisit the basics and showcase my skills to potential recruiters. Today, I set up my environment and Filtering Data in MySQL by Indexing and Views. I have selected data from tables which was created from sql-learning-day 1. This is just the beginning. Stay tuned for more SQL practice and insights over the 15 days!
### Indexing in MySQL is a technique used to optimize the performance of a database by improving the speed of data retrieval operations. An index is a data structure that allows MySQL to find records more quickly and efficiently, similar to an index in a book that helps you locate information faster.
### Indexing in MySQL can significantly improve the performance of database operations, particularly when dealing with large datasets.
### A view in MySQL is a virtual table that is created based on the result set of a SQL query. It does not store data physically like a regular table but acts as a stored query that can be reused. Views can simplify complex queries by encapsulating them into a single, reusable structure.
First i have inserted some data's and selected
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table%201.png)
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table2.png)
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table3.png)
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table%204.png)
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table5.png)
![image alt](https://github.com/Udayagour14/sql-learning-2/blob/main/sql%20table%206.png)


![image alt](https://github.com/Udayagour14/indexing-and-View-in-MySQL/blob/main/sql8.1.png)
![image alt](https://github.com/Udayagour14/indexing-and-View-in-MySQL/blob/main/sql8.2.png)
## Benefits of Views:
Simplification: Complex queries can be encapsulated into views, making them easier to use.
Security: Views can be used to restrict access to specific data. For example, you can create a view that only shows certain columns of a table, hiding sensitive data.
Reusability: Views can be reused across multiple queries, reducing code duplication.
Data Abstraction: Views can present data in a way that is meaningful to the user, even if the underlying data structure is complex.
## Drawbacks of Views:
Limited Functionality: Some operations (like INSERT, UPDATE, DELETE) are not allowed or can be complex when performed on views that are based on multiple tables.

![image alt](https://github.com/Udayagour14/indexing-and-View-in-MySQL/blob/main/sql8.3.png)
![image alt](https://github.com/Udayagour14/indexing-and-View-in-MySQL/blob/main/sql8.4.png)
## Benefits of Indexing:
Faster query performance, especially for SELECT statements.
Efficient data retrieval for large datasets.
Helps in maintaining the uniqueness of data with unique indexes.
## Drawbacks of Indexing:
Indexes take up additional storage space.
They can slow down data insertion, update, and deletion operations because the index also needs to be updated.

