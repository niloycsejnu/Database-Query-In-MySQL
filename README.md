# Database Query Project

This repository contains a series of MySQL database queries with their results, along with a supporting SQL file for the database schema and data. All queries are executed using **DBeaver** and **XAMPP MySQL**.

---

## Project Structure

- **`queries and outputs.docx`**: Contains all the queries along with their outputs as screenshots.
- **`studentdb.sql`**: SQL file containing the table structure and data used in the project.
---

## Queries Included

1. **Find Students by Blood Group**  
   Query to retrieve the first name, last name, phone number, and address of students with the blood groups `O+` and `A-`.

2. **Find Subject and Department Details**  
   Query to fetch the department name, department code, and subject title for the subject with code `EE201`.

3. **Count of Students by Blood Group**  
   Query to display the count of students for each blood group with at least 2 students.

4. **Find Students by Department**  
   Query to get the first name, last name, and subject title of students enrolled in the department `CS101`.

5. **Total Semester Fee Collection**  
   Query to calculate the total semester fee collected for the Computer Science department.

6. **Update Semester Fee**  
   Query to increase the semester fee by 10% for students in the `CS101` department.

7. **Students and Teachers in CS101**  
   Query to find the students' first name, last name, and their teacher’s first name and designation in the course `CS101`.

8. **Same City Students and Teachers**  
   Query to display the student's first name and the teacher's last name where both belong to the same city.

9. **Students in "Algorithms"**  
   Query to list the students' first name, last name, email, subject code, and subject title for those enrolled in the subject `Algorithms`.

10. **Promote Teachers**  
    Query to update the designation of teachers:
    - Lecturers are promoted to Sr. Lecturers.
    - Sr. Lecturers are promoted to Associate Professors.

11. **Teacher with Second Highest Salary**  
    Query to find the first name and last name of the teacher with the second highest salary.

12. **Teacher and Students for Second Highest Salary**  
    Query to list the first name and last name of the teacher with the second highest salary and details of the students enrolled in their course. Includes student’s first name, last name, city, and department code.

---

## Tools Used

- **XAMPP MySQL**: For hosting and running the database locally.
- **DBeaver**: For writing and executing SQL queries and visualizing results.

---

## How to Use

1. Import the `database_schema.sql` file into your MySQL server.
2. Open the `queries_and_outputs.docx` file to review the queries and their outputs.
3. Use DBeaver to execute the queries for live results.
4. Modify or expand the queries as needed to suit your database requirements.

---

## Screenshots

All query outputs are provided as screenshots in the `queries_and_outputs.docx` file for reference.

---

Feel free to reach out for any queries or suggestions!

