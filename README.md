# SQL Query Assignment – University Schema

This project contains SQL queries executed using the **University Schema**, based on the sample data provided in `smallRelationsInsertFile.sql`.

Below is a summary of the assignment tasks, grouped by section.

---

## Section 1: Basic SQL Queries

Write the following queries in SQL using the university schema:

**6.a.** Find the titles of courses in the Comp. Sci department that have 4 credits. 

<img width="468" alt="image" src="https://github.com/user-attachments/assets/5c347909-e55a-446d-853e-de9c89d34e93" />

**6.b.** Find the name(s) of the instructor(s) who **don’t** earn the lowest salary in the Physics department.  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b670bc75-5183-4689-b4f7-9df14fe8f308" />


**6.c.** Find the enrollment of each section (number of students enrolled) that was offered in Fall 2017.  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/0c6f0d09-fc98-413d-9782-331bf031a316" />


**6.d.** Find the **minimum enrollment**, across all sections offered in Fall 2017.  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/592981c7-b412-4891-b12a-604871f2c78d" />


**6.e.** Find the **course ID and section ID** of the sections that had the **minimum enrollment** in Fall 2017.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/ad59c48f-da8e-456a-a062-f12274d3b2b9" />



---

## Section 2: Advanced SQL Queries with Execution

Write the following queries in SQL using the university schema, execute them on the sample database (`smallRelationsInsertFile.sql`), and document both the SQL and the result screenshots.

**7.a.** Find the names of all students who have taken at least **two courses offered by the Comp. Sci. department**. Make sure there are no duplicate names in the result. *(Note: Students from other departments can also take Comp. Sci. courses.)*  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b65e01ed-cf22-4524-8b17-9f38d7395c68" />


**7.b.** Find the **IDs and names** of all students who have **not taken any course offering in 2017**. 

<img width="468" alt="image" src="https://github.com/user-attachments/assets/70e26f12-1292-4b36-9f18-faca87c70789" />


**7.c.** For **each department**, find the name and salary of the **instructor who earns the minimum salary** in that department. *(Assume every department has at least one instructor.)*  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/92d9b60d-5a2e-4def-9cf2-c1a179b2c78e" />


**7.d.** Find the **highest** (across all departments) of the **per-department minimum salary** computed in part 7.c.  

<img width="468" alt="image" src="https://github.com/user-attachments/assets/dfc86ef0-b836-46a9-a94c-e2bf2117539e" />


**7.e.** Find the course titles of all **prerequisite courses** of **“CS-319”**.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/7516f4a9-7e40-4de2-b599-1d954050c491" />


---

## 📎 Notes

- Screenshots of the executed queries and their results are included in the `/images/` folder.
- SQL script used: [`smallRelationsInsertFile.sql`](./sql/smallRelationsInsertFile.sql)

