# Backend-Task

Build a REST api in node using express and mongo:

(1.) Design a Student and Course Schema using Mongoose:  
- Student schema should at least have the following fields: name, email, phone, city, country, courseId etc. 
- Course schema should have the following fields name, teacher  etc. 

(2.) Create an API where you can do the following things: 
- Get list of all students (should support pagination and search)
- Get a single student 
- Create new student record
- Update a record
- Delete a record 

(3.) Create another api where you can get all the counts of students in courses along with course name and teacher. You need to do this via MongoDb Aggregation.
