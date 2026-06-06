# Mongo_db_Aggregation_Exercise

Overview

This project contains MongoDB aggregation exercises implemented using Node.js and the MongoDB driver. The exercises demonstrate common aggregation operations such as grouping, filtering, sorting, and joining collections using $lookup.

Technologies Used
Node.js
MongoDB
MongoDB Compass
MongoDB Node.js Driver

Database

Database Name:

group_by

Collections:

students

Sample document:

{
  "name": "Alice",
  "student_email": "alice@example.com",
  "year": 2,
  "gpa": 3.8
}


orders

Sample document:

{
  "student_email": "alice@example.com",
  "item": "Laptop",
  "total": 50000
}

Exercises
Exercise 1: Group Products by Tag
Use $unwind on the tags array.
Group products by tag.
Count products for each tag.
Sort results by count in descending order.


Exercise 2: Average GPA by Year
Filter students with GPA greater than 3.0.
Group students by year.
Calculate average GPA.
Round GPA to 2 decimal places.


Exercise 3: Join Orders and Students
Use $lookup to join orders and students.
Match records using student_email.
Display:
->Student Name
->Student Email
->Item
->Total


Learning Objectives


MongoDB CRUD Operations
Aggregation Pipelines
$match
$group
$project
$sort
$unwind
$lookup
MongoDB Integration with Node.js
