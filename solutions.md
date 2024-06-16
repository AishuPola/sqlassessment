```sql
CREATE TABLE Students (
    student_id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    date_of_birth DATE,
    email VARCHAR(100),
    phone_number bigint
);


-- Insert data into Students Table
INSERT INTO Students (student_id, first_name, last_name, date_of_birth, email, phone_number) VALUES
(1, 'Alice', 'Smith', '2000-01-01', 'alice.smith@gmail.com', 9000906504),
(2, 'Bob', 'Johnson', '2001-02-02', 'bob.johnson@gmail.com', 9666945460),
(3, 'Charlie', 'Brown', '2001-03-03', 'charlie.brown@gmail.com', 8688061790),
(4, 'David', 'Williams', '2003-04-04', 'david.williams@gmail.com', 7702623604),
(5, 'Eva', 'Davis', '2002-05-05', 'eva.davis@gmail.com', 8309808588),
(6, 'Frank', 'Miller', '2000-06-06', 'frank.miller@gmail.com', 9886406851),
(7, 'Grace', 'Wilson', '2001-07-07', 'grace.wilson@gmail.com', 9010235678);


--1. Write an SQL query to insert a new student named John Doe into the "Students" table.
insert into Students(student_id, first_name, last_name, date_of_birth, email, phone_number) values
(8,'john','Doe','2003-03-06','john.doe@gmail.com',9948361612);
```

