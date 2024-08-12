# Books and Authors Database
This project is a SQL-based database that stores information about books and their authors. The database allows you to manage authors, their nationalities, and the books they have written. You can also perform various queries to retrieve information, such as finding out which author has written the most books or how many books belong to authors from a particular nationality.

# Project Structure
Tables:

Authors: Stores information about the authors, including their first name, last name, and nationality.
Books: Stores information about books, including the title, author, and description.
Relationships:

The Books table is connected to the Authors table through a foreign key (author_id), establishing a relationship between books and their respective authors.

#SQL Schema
<img src="https://github.com/user-attachments/assets/d0a76aab-9158-4254-a80c-eb68bb31d1a0" />


#Sample Data Insertion
Inserting Authors:
<img src="https://github.com/user-attachments/assets/eac4e563-029d-44dc-963d-6de2c1a45156" />

Inserting a Book:
<img src="![2](https://github.com/user-attachments/assets/0bda3b31-9cec-42a3-8fac-c4aa12b6b2a5" />

#Queries
Find the author with the most books:
<img src="https://github.com/user-attachments/assets/464675ba-957d-44a4-8bbe-3eed95d0674e" />

Count the number of books by authors' nationality:
<img src="![3](https://github.com/user-attachments/assets/4dde6517-8546-44fc-ba66-d9c92657448f" />



