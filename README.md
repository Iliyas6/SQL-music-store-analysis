🎵 Music Store SQL Analysis Project (Chinook Dataset)

This project contains a complete SQL analysis of a digital music store using the Chinook-style database.
It includes raw Excel data, SQL scripts, schema diagrams, and advanced analysis queries used to answer real business questions such as:

Who are the top customers?

Which artists generate the most revenue?

What is the most popular genre by country?

What city spends the most on music?

What tracks are longer than average?

📁 Project Structure
Music Store SQL Project
│
├── 📁 Excel Raw data
│      ├── album.xlsx
│      ├── artist.xlsx
│      ├── customer.xlsx
│      ├── employee.xlsx
│      ├── genre.xlsx
│      ├── invoice.xlsx
│      ├── invoice_line.xlsx
│      ├── media_type.xlsx
│      ├── playlist.xlsx
│      ├── playlist_track.xlsx
│      ├── track.xlsx
│
├── 📁 SQL Database File
│      ├── Music_Store_database.sql
│      ├── Music_Store_Query.sql
│      ├── SQL Music Questions2.sql
│      ├── Music Store – Create Tables Query.txt
│
├── 📁 SQL Schema & Diagram
│      ├── MusicDatabaseSchema.png
│      ├── schema_diagram.png
│
├── 📁 Questions and Documentation
│      ├── Music Store Analysis Questions.pdf
│      ├── Notes / Readme / Explanation
│
└── README.md  

🗄️ About the Dataset (Chinook Music Store)

The dataset represents a realistic digital music store where customers purchase tracks, albums, playlists, and more.
It contains information about:

Customers

Employees

Artists

Albums

Tracks

Genres

Invoices & Invoice Lines

Playlists

This structure makes it ideal for practicing SQL joins, aggregations, CTEs, window functions, and data analysis.

🧩 Database Schema

Below is the schema diagram representing the relationships among all tables.

📌 Full Database Schema
<img width="710" height="574" alt="MusicDatabaseSchema" src="https://github.com/user-attachments/assets/1a4f50b6-59b9-4d1b-b986-627841e0750c" />

📌 Table Relationship Diagram
<img width="594" height="598" alt="schema_diagram" src="https://github.com/user-attachments/assets/616cde94-3e4e-45d4-a9af-f63d03482fbf" />


📊 Business Questions Solved in This Project

This project answers more than 15+ analytical SQL questions, such as:

✔ Best Customer

Identify the customer who spent the most.

✔ City with Highest Revenue

Used to decide where to host a music festival.

✔ Rock Music Listeners

Email list of all customers who listen to Rock music.

✔ Top 10 Artists With Most Rock Tracks

Ranking based on number of rock songs.

✔ Tracks Longer Than Average

List of songs whose duration is above the average.

✔ Spending by Customer on Each Artist

Customer-wise revenue contribution for each artist.

✔ Most Popular Genre by Country

Genre with maximum purchases per country (including ties).

✔ Top Customer Per Country

Customer who spent the most in each country.

All queries are available inside:
Music_Store_Query.sql and SQL Music Questions2.sql.

🛠️ Technologies Used

MySQL / PostgreSQL / SQL Server

SQL Joins (INNER/LEFT)

Aggregations & Grouping

CTEs

Subqueries

Excel Data Cleaning

Database Schema Design

📘 How to Use This Project

Import the SQL file:
Music_Store_database.sql

Explore or modify the schema if needed.

Run analytical queries from:
Music_Store_Query.sql

Check the PDF file for question descriptions.

View schema diagrams in the SQL Schema & Diagram folder.

📚 Key Files
File / Folder	Purpose
Excel Raw Data	Original dataset files
Music_Store_database.sql	Database creation + insert statements
Music_Store_Query.sql	All SQL analysis queries
SQL Schema & Diagram	ER diagram and schema images
Music Store Analysis Questions.pdf	Business questions
Notes / Documentation Folder	Explanations & notes

⭐ Author
Mohammed Iliyas
Engineer | Data Analyst | SQL | Power BI | Python
