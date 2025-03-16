# MySQL-Concepts-in-SQL Project

![Certificate of Completion](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Certificate%20of%20Completion.png)

This repository showcases my work and progress from an intermediate MYSQL course. The course covered a range of SQL concepts, some of which were more advanced, including transactions, views, triggers, and events. The goal of this project is to demonstrate my ability to work with various SQL concepts and implement them effectively within a database.

By completing this project, I have achieved the following learning objectives:


## Understand Data Manipulation Language (DML) Concepts:
I gained a strong understanding of how to use DML commands such as INSERT, UPDATE, DELETE, and SELECT to modify and query data in SQL databases.

## Understand Transaction Control Language (TCL) Concepts:
I learned how to manage transactions using commands like START TRANSACTION, COMMIT, and ROLLBACK to ensure data consistency and integrity.

## Understand Views in SQL:
I created views, virtual tables used to simplify querying and present data in a more user-friendly format.

## Understand Triggers in SQL:
I practiced creating triggers, automated actions that occur when specific database events (such as data changes) happen.

## Understand Events in SQL:
I set up events to automate scheduled tasks in the database, such as inserting data at specific times.

## Final Thoughts
Through this project, I have gained hands-on experience working with core SQL concepts such as **DML**, **TCL**, **views**, **triggers**, and **events**. 
This project has helped me build a solid foundation for performing data manipulation and automation tasks within a relational database.

---

# Project Screenshots

Here is a list of screenshots for the **Data Manipulation Language** (DML) Commands I took during the project:

### 1. **SELECT - Query to View Data**
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4355).png)

### 2. **INSERT - Adding a New Record**
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4356).png)

### 3. **UPDATE - Modifying the Exiating Record**
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4357).png)

### 4. **DELETE - Removing a Record** The First screenshot is Before, and he second screenshot is After
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4379).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4380).png)

---

### Transaction Control Language (TCL) - Manage transactions in a Database 

In this section, I worked with **Transaction Control Language (TCL)** commands to manage a transaction between two accounts in the database. 
I started the transaction with `START TRANSACTION`, checked if Emma Smith's balance was sufficient, and set the transfer amount to 50 using the `SET` command. 
Then, I updated the balances of both Emma Smith's account (by subtracting 50) and Peter White's account (by adding 50). 
Finally, I used `COMMIT` to finalize the transaction and save the changes to the database
and demonstrated how to **ROLLBACK** the transaction to revert any changes made. 
This exercise taught me how to ensure data integrity during transactions and how to permanently commit changes.

![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4360).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4363).png)

---

### VIEWS - virtual tables that simplify complex queries by presenting data from one or more tables in a specific format

![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4365).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4366).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4367).png)

---

### DELIMETER and TRIGGER - DELIMETER temporarily changes the statement separator, and a trigger automatically runs predefined actions in response to specific events on a table

![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4371).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4372).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4373).png)

---

### EVENTS - a scheduled action that automatically executes a predefined SQL statement or set of statements at a specified time or interval

I created a new table called information in the bookstore database and defined two events: eventOne, which inserts a row with the current timestamp when triggered,
and eventTwo, which inserts a row with the value 'SecondEvent' and timestamp, scheduled to run 1 minute later and preserved after completion.

![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4374).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4375).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4376).png)
![](https://github.com/TammyTheAnalyst/MySQL-Concepts-in-SQL/blob/main/Screenshot%20(4377).png)

