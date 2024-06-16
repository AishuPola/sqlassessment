### SQL Assessment Instructions

**Assessment Overview:**
This assessment is designed to evaluate your proficiency in SQL through practical tasks encompassing data manipulation, query formulation, and complex joins and subqueries. The questions are based on a hypothetical Student Information System (SIS) database comprising tables for Students, Courses, Enrollments, Teachers, and Payments. Ensure to create your own data for testing your queries.

**Database Tables:**

1. **Students**

   - `student_id` (Primary Key)
   - `first_name`
   - `last_name`
   - `date_of_birth`
   - `email`
   - `phone_number`

2. **Courses**

   - `course_id` (Primary Key)
   - `course_name`
   - `credits`
   - `teacher_id` (Foreign Key)

3. **Enrollments**

   - `enrollment_id` (Primary Key)
   - `student_id` (Foreign Key)
   - `course_id` (Foreign Key)
   - `enrollment_date`

4. **Teachers**

   - `teacher_id` (Primary Key)
   - `first_name`
   - `last_name`
   - `email`

5. **Payments**
   - `payment_id` (Primary Key)
   - `student_id` (Foreign Key)
   - `amount`
   - `payment_date`

**Questions:**

1. Write an SQL query to insert a new student named John Doe into the "Students" table.
2. Write an SQL query to enroll an existing student in a course, specifying the enrollment date.
3. Update the email address of a teacher in the "Teachers" table.
4. Write an SQL query to delete a specific enrollment record, choosing based on the student and course.
5. Update a course to assign a specific teacher using the "Courses" table.
6. Write an SQL query to calculate the total payments made by a specific student.
7. Retrieve a list of courses along with the count of students enrolled in each.
8. Find the names of students who have not enrolled in any course.
9. Retrieve the first name and last name of students, along with the names of the courses they are enrolled in.
10. List names of teachers and the courses they are assigned to.
11. Calculate the average number of students enrolled in each course using aggregate functions and subqueries.
12. Identify the student(s) who made the highest payment using a subquery.
13. Retrieve a list of courses with the highest number of enrollments using subqueries.
14. Calculate the total payments made to courses taught by each teacher using subqueries.
15. Identify students who are enrolled in more than one course.

Please make sure to create your own data for these tables to test your queries effectively.
