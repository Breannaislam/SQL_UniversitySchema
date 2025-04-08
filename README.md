# SQL Query Assignment – University Schema

This project contains SQL queries executed using the **University Schema**, based on the sample data provided in `smallRelationsInsertFile.sql`.

Below is a summary of the assignment tasks, grouped by section.

---

## Section 1: Basic SQL Queries

Write the following queries in SQL using the university schema:

**6.a.** Find the titles of courses in the Comp. Sci department that have 4 credits.  
<img width="468" alt="image" src="https://github.com/user-attachments/assets/5c347909-e55a-446d-853e-de9c89d34e93" />

**6.b.** Find the name(s) of the instructor(s) who **don’t** earn the lowest salary in the Physics department.  
**6.c.** Find the enrollment of each section (number of students enrolled) that was offered in Fall 2017.  
**6.d.** Find the **minimum enrollment**, across all sections offered in Fall 2017.  
**6.e.** Find the **course ID and section ID** of the sections that had the **minimum enrollment** in Fall 2017.

---

## Section 2: Advanced SQL Queries with Execution

Write the following queries in SQL using the university schema, execute them on the sample database (`smallRelationsInsertFile.sql`), and document both the SQL and the result screenshots.

**7.a.** Find the names of all students who have taken at least **two courses offered by the Comp. Sci. department**. Make sure there are no duplicate names in the result. *(Note: Students from other departments can also take Comp. Sci. courses.)*  
**7.b.** Find the **IDs and names** of all students who have **not taken any course offering in 2017**.  
**7.c.** For **each department**, find the name and salary of the **instructor who earns the minimum salary** in that department. *(Assume every department has at least one instructor.)*  
**7.d.** Find the **highest** (across all departments) of the **per-department minimum salary** computed in part 7.c.  
**7.e.** Find the course titles of all **prerequisite courses** of **“CS-319”**.

---

## 📎 Notes

- Screenshots of the executed queries and their results are included in the `/images/` folder.
- SQL script used: [`smallRelationsInsertFile.sql`](./sql/smallRelationsInsertFile.sql)

