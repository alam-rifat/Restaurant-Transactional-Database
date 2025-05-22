# Restaurant-Transactional-Database

*Remarks: This project aimed to design and implement a comprehensive transactional database system for a restaurant. It offered me practical experience in the entire database development lifecycle. I gained functional experience implementing the database using SQL DDL statements, achieved familiarity with a database management system like Access, and developed a user-facing application with forms for data interaction and queries/reports for business insights.*

This project outlines the development of a transactional database for a restaurant management system. It is designed to manage various aspects of the restaurant's operations, including customer information, reservations, orders, payments, inventory, and employee data.

* **ER Model & Relational Model:** An Entity-Relationship (ER) model is used to define entities such as Customer, Reservation, Order, Employee, Dish, Payment, and Inventory, along with their relationships. This ER model is then converted into a relational model, specifying the schema for each table with primary and foreign keys.

* **Normalization:** The normalization occurs up to the third normal form. This involves splitting attributes (like addresses) to satisfy 1NF, creating new tables to resolve partial dependencies (for 2NF, e.g., creating OrderDish from Dish and DishInventory from Inventory), and creating tables like "Location" to address transitive dependencies (for 3NF in Customer and Employee tables).

* **SQL Implementation & Access Schema:** SQL CREATE TABLE statements are provided for establishing the database schema and defining tables. Microsoft Access was used to host the database, including storing relationships and SQL queries for joining multiple tables.

The database system is presented as a tool to effectively integrate restaurant operations, enhance customer management and satisfaction, and ensure data consistency and integrity through normalization and SQL implementation. The overall goal is to streamline operations and support the restaurant's long-term success.

