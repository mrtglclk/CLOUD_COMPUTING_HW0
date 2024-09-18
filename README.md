# CLOUD_COMPUTING_HW0

## Project Overview
This project integrates three repositories: Database, Application, and UI, to provide a comprehensive end-to-end solution for managing course sections.

---

## Table of Contents
- [Database](#database)
- [Application](#application)
- [UI](#ui)
- [Screenshots](#screenshots)
- [Additional Functionality](#additional-functionality)
- [Submission Instructions](#submission-instructions)

---

## Database

### Steps to Set Up the Database Repository

1. **Install MySQL**: Ensure MySQL server is installed and running on your local machine.
2. **Create Database**: Execute the following SQL commands to create the database and the required table:
   ```sql
   CREATE DATABASE IF NOT EXISTS p1_database;

   USE p1_database;

   CREATE TABLE IF NOT EXISTS course_sections (
       course_id     BIGINT NULL,
       course_name   TEXT   NULL,
       uuid          TEXT   NULL,
       created_at    TEXT   NULL,
       course_code   TEXT   NULL,
       sis_course_id TEXT   NULL,
       course_no     TEXT   NULL,
       section       TEXT   NULL,
       course_year   TEXT   NULL,
       semester      TEXT   NULL
   );
