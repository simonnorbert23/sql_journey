# sql_journey
This is a journal of how I'm learning SQL

## Some theory

A database is... 
  * ...a collection of data
  * ...a method for accessing and manipulating data
  * ...a structured set of computerized data with an accessible interface
  
An RDBMS (Relational Database Management System) is an interface for the database and lets us (or our application) access the database.

A table is...
  * ...the heart of a database
  * ...where the actual information is stored
  * ...a collection of related data held in a structured format within a database
The headers of a table are called columns. Creating the columns provides an empty structure to be filled with data. 
The actual data is stored in rows.

Main types of data:
* INT = an integer or a whole number, max signed value 2147483647
* VARCHAR = a variable-length string, can specify a max number of characters allowed in a column as VARCHAR(42)

|Username  VARCHAR(15)|Content VARCHAR(140)  |Favorites INT|
|---------------------|----------------------|-------------|
|'coolguy'            |'my first tweet!'     |1            |
|'guitar_queen'       |'I love music :)'     |10           |
|'lonely_heart'       |'still looking 4 love'|0            |


## MySQL vs. SQL

* SQL is the language we use to communicate with our databases. Here's a humanized version of an SQL query: "Find the customers called Jim"
* Working with MySQL is essentially writing SQL code.
* SQL is a standard that RDBMS-s implemennt. 
* There are slight differences in how the RDBMS-s implement the language.
* Once you know SQL it's quite easy to switch between RDBMS-s.
* RDBMS-s are unique in what features they offer (security, speed, etc.), not in their language/syntax.
