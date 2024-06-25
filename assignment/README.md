# Week 1: Introduction & Foundational Skills (Focus on Project Relevance)

This week, we'll be diving into the exciting world of SQL and databases! We'll explore what SQL is used for, how it benefits web applications, and the building blocks of databases: tables, columns, and data types. But most importantly, we'll get our hands dirty by creating a basic database structure for our upcoming Expense Tracker project!

## Learning Objectives:
Understand the purpose and applications of SQL, particularly for web applications.
Identify the fundamental components of a database: tables, columns, and data types.
Design a basic database schema for our Expense Tracker project.
Instructions
This assignment is designed to be completed in approximately 2 hours.

**What you'll need:**

Access to a computer with internet access
A text editor (Microsoft Word document)
Drawing software (e.g. Draw.io, visual paradigm) for the bonus question.

_________________________________________________________________________________________________________________________
## Submission:

Save your completed assignment as a document (e.g., .docx, pdf)
Submit your document through the designated course platform.
_________________________________________________________________________________________________________________________

## Part 1: Understanding SQL (30 minutes)

**Question 1. Research**

Use online resources like websites or PowerPoint slides.

**1.1.** In a single Word document, summarize your findings in a short paragraph (3-5 sentences).
Web Applications:  

Imagine a dynamic website like an online store. How do you think SQL plays a role in managing data behind the scenes? Consider how product information, user accounts, and order details might be stored and accessed.

**1.2. ** Write a short explanation (3-5 sentences) in your document about the role of SQL in web applications.

SQL is essential for web application development, providing robust tools for data storage, retrieval, and manipulation. It ensures data integrity through constraints and enables secure data access with role based controls, protecting sensitive information. SQL also enhances application performance with indexing, allowing efficient data retrieval. Additionally, it simplifies complex queries facilitating the management and transformation of large data sets. Overall SQL capabilities in handling data efficiently and securely are vital for smooth operation and reliability of web application.


**1.3.** List 3 benefits of using SQL for web applications.

* EFFICIENT DATA MANAGEMENT: it provides a structured and organized way to manage data allowing for efficient storage retrieval and manipulation of large sets of data
* DATA INTEGRITY AND ACCURACY: it ensures integrity through constraints like primary key, foreign keys, and unique constraints ensuring data stored is accurate, consistent, and free from duplicates.
SCALABILITY: SQL data bases are designed to handle growth in terms of user load and data volume.

**1.4.** Think about efficiency, data organization, and data retrieval capabilities. Briefly explain each benefit in your document (1-2 sentences per benefit).
1. EFFIECNCY; efficient databases lead to improved performance to handle data operations quickly, reducing latency and response time.
2. DATA ORGANIZATION: well organized data makes it easier to retrieve information.
3. DATA RETRIVAL: fast data retrieval ensures that queries are processed quickly.

**1.5. ** List any 3 Database Management Systems. 
* MONGODB
* MySQL
* PostgreSQL

## Part 2: Database Fundamentals (45 minutes)

**Question 2.1: Tables**

Think about how data is organized in rows and columns.
In your document, define a database table and explain its similarity to a spreadsheet (2-3 sentences).
> A DATABAE TABLE is a structured set of data held within a database.   Both database and spread sheets share grid like structures and support data manipulation, storage, managing large-scale data, ensuring data integrity and supporting complex queries and analysis.

**Question 2.2: Columns**

Consider different types of data like text, numbers, and dates.
* Define "columns" and provide an example with an explanation (2-3 sentences) in your document.
* A column refers to a vertical arrangement of data within a table or a grid-like structure.
* NAME* AGEDOBJOHN DOE24 2000-01-01ELLA MAE21 2003-04-07*  THE ELEMENTS IN THE VERTICAL ARRENGMENT ARE THE COLUMNS WHILE ELEMENTS IN THE HORIZONTAL ARRENGMENT ARE THE ROWS.
Data Types: Why are data types important in a database? Briefly explain 3 common data types (e.g., Text, Number, Date).
> Data type in db specify the kind of values that can be stored and manipulated within a program or a database.
1. INTEGER denoted as INT stores whole numbers without decimals example’1’
2. Character/string (CHAR, VARCHAR)-stores textual data such as letters, numbers symbols and spaces.
3. BOOLEAN- BOOLEAN DATA stores binary values representing true or false.

**Question 2.3: Data Types**

Think about how data types ensure data integrity and efficient storage.
Explain the importance of data types and provide brief explanations of 3 common types (2-3 sentences each) in your document.
* Data types play a critical role in ensuring data integrity and efficiency Choosing appropriate data types ensures optimization of storage space and data accuracy by ensuring constraints.
* INTEGER INT crucial for sorting whole numbers without decimals, ensuring numerical accuracy and minimizing storage requirements. Usually used for primary keys, ids and numerical computational database.
* CHARACTER/STRING(VARCHAR): This data type allows for flexible input of data in variable-length. They optimize storage by only using space proportional to the actual data length.
* BOOLEAN (BOOL): This are essential for storing binary statements (‘true’ or ‘false’). They accurately represent logical conditions and flags within databases, aiding in decision making processes and data validation 
  
## Part 3: Expense Tracker Database Design (45 minutes)

**3.1. Planning: ** 
We'll be building an Expense Tracker application. What kind of data do you think we'll need to track? List at least 5 data points relevant to our project.
* Expenses detail.
* Payment method.
* Income budget.
* User profile setting.
* Reporting analytics.
* Security access control.

* Consider information like expense amount, date, and category.
* List your identified data points in your document.
All the above falls under expenses details

 

**3.2. Tables: ** 
Considering the data points, you listed, design a basic database schema with one main table (likely named "Expenses").

* Define the columns needed for this table.
* Food.
* Transportation.
* Shopping.
* Utilities.
* Entertainment.
* Loans and savings.
* Assign appropriate data types to each column based on the kind of data it will hold. (e.g., amount: number, date: date, category: text)
1. Date 
2. Amount 
3. Recurring
4. Category
5. Expense_id
  
  In your document, create a table structure that includes:
* Table name (e.g., Expenses)
* Column names (e.g., expense_id, amount, date, category)
* Data type for each column (e.g., INT, DECIMAL, DATE, TEXT)
EXPENSES
Expense_idAmountDateCategoryRecurring143252024-06-01foodfalse21002024n-06--01Transporttrue325002024n-06--01shoppingfalse423002024-01-06Entertainmenttrue

## Bonus:  

Sketch a simple Entity Relational Diagram (ERD) of your table structure, including column names and data types.

Use drawing software or a simple table format to visually represent your schema.

** Remember: There might be multiple ways to design your database schema. The goal is to understand the concepts and create a logical structure to store our expense tracking data.

  _________________________________________ _WELLDONE_ _____________________________________________

