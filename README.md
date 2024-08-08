# Books and Authors Database
This project is a SQL-based database that stores information about books and their authors. The database allows you to manage authors, their nationalities, and the books they have written. You can also perform various queries to retrieve information, such as finding out which author has written the most books or how many books belong to authors from a particular nationality.

# Project Structure
Tables:

Authors: Stores information about the authors, including their first name, last name, and nationality.
Books: Stores information about books, including the title, author, and description.
Relationships:

The Books table is connected to the Authors table through a foreign key (author_id), establishing a relationship between books and their respective authors.

#SQL Schema

#Sample Data Insertion
Inserting Authors:

Inserting a Book:

#Queries
Find the author with the most books:


Count the number of books by authors' nationality:


