# Book Database Analysis Using SQL

## Project Overview

This project analyzes a relational database containing information about books, authors, publishers, ratings, and reviews. The goal was to generate insights that could support the development of a digital reading platform by understanding publishing activity, reader engagement, and user behavior.

The analysis was conducted using SQL queries executed through PostgreSQL and Python.

---

## Business Questions

The analysis focused on answering the following questions:

* How many books were published after January 1, 2000?
* How many reviews and what average rating does each book receive?
* Which publisher has released the largest number of substantial books (more than 50 pages)?
* Which author has the highest average rating among books with at least 50 ratings?
* How actively do highly engaged users contribute written reviews?

---

## Database Structure

The database consists of five related tables:

* **books** – book information and publication details
* **authors** – author information
* **publishers** – publisher information
* **ratings** – user ratings
* **reviews** – written user reviews

Relationships between tables are primarily established through `book_id`, enabling the combination of book information with ratings, reviews, authors, and publisher data.

---
### Database Schema
<img width="822" height="522" alt="database_schema" src="https://github.com/user-attachments/assets/bf8570d3-87ea-4e9a-9467-9f2ff5e5c8b8" />

---

## Tools Used

* SQL
* PostgreSQL
* Python
* Pandas
* SQLAlchemy

---

## Key Findings

* Identified **819 books** published after January 1, 2000.
* *Twilight* was the most-reviewed book, receiving **7 written reviews**.
* Among the most-reviewed books, *Harry Potter and the Prisoner of Azkaban* achieved the highest average rating (**4.41**).
* **Penguin Books** published the largest number of substantial books, contributing **42 titles** with more than 50 pages.
* **J.K. Rowling and Mary GrandPré** achieved the highest average author rating (**4.29**) based on **310 ratings**.
* Users who rated more than 50 books wrote an average of **17.46 reviews**, indicating that highly engaged readers also contribute valuable written feedback.

---

## SQL Skills Demonstrated

* Common Table Expressions (CTEs)
* JOINs and LEFT JOINs
* Aggregation Functions (`COUNT`, `AVG`)
* GROUP BY and HAVING
* Filtering and Sorting
* Relational Database Analysis
* Business-Oriented SQL Reporting

---

## Recommendations

* Encourage users to submit more written reviews to increase qualitative feedback and improve recommendation quality.
* Prioritize highly rated books and authors within recommendation systems and promotional campaigns.
* Strengthen partnerships with major publishers such as Penguin Books to expand content offerings.
* Develop engagement strategies for highly active users, as they contribute valuable ratings and written feedback.
* Continue expanding the catalog of modern publications to align with contemporary reader interests.

---

## Repository Contents

* `Book_Database_Analysis_Using_SQL.ipynb` – Complete SQL analysis notebook
* `README.md` – Project documentation

## Author

Sandra Quinones
