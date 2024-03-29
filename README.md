# HBaseDatabase
Creating and Manipulating an HBase Database Using Docker


#### Column-oriented schemas
<img src="https://github.com/CatelloTheDataProjectManager/HBaseDatabase/blob/main/column-oriented%20schema.png" width="400">

Here are some of the main advantages of column-oriented schemas:

- Improved query performance for certain types of queries
- Better compression of data
- Flexible schema design
- Efficient storage and retrieval of sparse data
- Support for time-series data and other specialized use cases

Column-oriented schemas can be particularly useful for big data and NoSQL databases, where data is often distributed across multiple nodes and query performance is a critical concern. However, they may not be the best choice for all types of applications or workloads, and careful data modeling and query design are important to ensure optimal performance.

### HBase Connection and Database Creation
This project focuses on connecting to an HBase database and creating a table using the Happybase library in Python. The project includes instructions on how to obtain the HBase IP address in a Docker environment and establish a connection to the database.

### Table Schema and Creation
The project covers the creation of a table named 'customer' with a specified schema. The schema includes two column families: 'address' and 'order'. The project demonstrates how to create a table in HBase using the Happybase library.

### Data Insertion
The project demonstrates how to insert data into the 'customer' table. It includes examples of inserting data into both the 'address' and 'order' column families for multiple clients.

### Data Retrieval
The project shows how to retrieve data from the 'customer' table. It includes examples of scanning the entire table and retrieving specific rows based on their key.

**Jupyter Notebook:** [HBase Database Project](https://github.com/CatelloTheDataProjectManager/HBaseDatabase/blob/main/Hbase_test.ipynb)

Feel free to explore the code and documentation to understand the project better. Your feedback and contributions are highly valued! 🚀
