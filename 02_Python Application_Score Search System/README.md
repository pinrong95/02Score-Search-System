# MySQL Student Record System

This system manages student scores in a MySQL database with features to:

1. Create a `STUDENTS` table with student details (ID, Name, Gender, and Subject Scores).
2. Insert student data via console input.
3. Query all student records from the database.
4. Import student scores from a CSV file.
5. Update specific student scores (e.g., change Sophia's English score to 99).
6. Calculate and display average scores for each subject.
7. Use `pandas` to calculate and show average scores by subject.

## Requirements

- Python 3.x
- MySQL 5.x+
- `MySQL-python` (MySQLdb)
- `pandas`

## Installation

1. Install MySQL and create a `PRACTICEDB` database.
2. Install dependencies:
    ```bash
    pip install MySQL-python pandas
    ```
3. Update the database credentials in the script.

## Features

- **Create Table**: Automatically creates the `STUDENTS` table.
- **Insert Data**: Insert student records via user input.
- **Query Data**: Display all student records.
- **CSV Import**: Import student data from a CSV file.
- **Update Scores**: Modify specific student scores (e.g., Sophia's English score).
- **Calculate Averages**: Display average scores for each subject, calculated using `pandas`.

## Example Usage

```bash
$ python student_record_system.py
enter name: John Doe
enter chinese score: 85
...

# Query all records
$ python student_record_system.py query

# Update Sophia's score
$ python student_record_system.py update_sophia_score

# Import data from CSV
$ python student_record_system.py import_csv data.csv
