# Creating-SQL-Database-

In this project, I built a database via MySQL Workbench for a public library to collect and analyze information about clients' reading interests, which will be used by the library's management to decide on future purchasing policies. The project focused on books and clients' interests in them.

First, I created SQL statements to establish the tables for the database, using the provided Entity Relationship Diagram (ERD). I implemented the tables with the necessary constraints, including primary and foreign keys, as well as relationships between tables.

Next, I populated the database with a given sample dataset. Following that, I wrote various SQL queries to retrieve specific information, such as client demographics, popular authors, borrowing trends, and genre preferences. Additionally, I created a VIEW to display titles borrowed by at least 20% of clients.

Additionally, I optimized my queries by creating indexes that increased their performance.

![Screenshot 2023-05-06 at 6 19 05 PM](https://user-images.githubusercontent.com/130959114/236652903-30fe4339-c5b1-4f86-bf5c-891585026310.png)


## Creating Indexes
- In order to improve the performance of my query I decided to employ a Index. An Index is a data structure that allows for fast lookups and retrieval of data based on certain criteria, such as a specific column or set of columns. By using an index, the database can quickly find the relevant data without having to scan the entire table, which can be especially helpful when dealing with large amounts of data. Indexes can speed up queries by reducing the amount of data that needs to be scanned, which can significantly improve query response times. In my database I decided to employ a a B-tree. 



## Employing Python 
Due to the large set of data, I employed Python to develop a sophisticated automation solution for formatting my dataset, enabling seamless integration with my SQL database.
![Screenshot 2023-05-06 at 6 20 38 PM](https://user-images.githubusercontent.com/130959114/236652939-ff7faffc-a3ff-4b5e-9b8d-ab423cc6a03e.png)

