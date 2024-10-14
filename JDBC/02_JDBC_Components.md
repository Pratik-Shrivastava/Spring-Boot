# JDBC Components

In addition to the JDBC drivers, there are several other components that make up the JDBC API, including:

## 1. `DriverManager` Class
- Contains the `getConnection()` method, which is used to establish a connection to the database.

## 2. `Connection` Interface
- An instance of the `Connection` interface is required to perform database operations such as executing SQL queries and managing transactions.

## 3. `Statement` and `PreparedStatement` Interfaces
- **Statement**: Used to execute basic SQL queries.
- **PreparedStatement**: A more efficient and secure way to execute queries, especially when dealing with input parameters. It is preferred over `Statement` as it helps prevent SQL injection and is optimized for repeated queries.

## 4. `ResultSet` Interface
- The `ResultSet` interface stores the result of a database query (usually in the form of a table). It allows iteration through the rows of the query result.

These components work together to provide a powerful and flexible API for working with databases in Java.
