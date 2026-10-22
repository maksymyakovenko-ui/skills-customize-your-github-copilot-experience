# 📘 Assignment: File I/O Mini-Project: Student Gradebook

## 🎯 Objective

Build a command-line gradebook in Python that saves student names and grades to a CSV file. Practice reading, writing, and updating persistent data with Python file I/O.

## 📝 Tasks

### 🛠️ Manage Student Grades

#### Description
Create a command-line program that lets a teacher enter student names and grades and view the records during the current run.

#### Requirements
Completed program should:

- Provide menu options to add a student grade, display all records, and quit.
- Store each record with a student name and a numeric grade from 0 to 100.
- Reject blank names and grades outside the 0–100 range.


### 🛠️ Save and Load the Gradebook

#### Description
Use a CSV file to preserve gradebook records between program runs.

#### Requirements
Completed program should:

- Read existing student records from a CSV file when the program starts.
- Write added records to the CSV file so they remain available after the program exits.
- Use the `csv` module and close files reliably, such as by using a `with` statement.
- Start with an empty gradebook if the CSV file does not exist yet.


### 🛠️ Summarize Class Grades

#### Description
Add a summary option that calculates useful information from the saved gradebook records.

#### Requirements
Completed program should:

- Display the number of recorded grades and the class average.
- Calculate the average correctly using all recorded grades.
- Show a clear message instead of dividing by zero when there are no records.
