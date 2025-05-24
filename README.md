# Student Data Tracker CLI Tool

## Project Setup

1.  **Prerequisites:**
    *   Python 3.6 or higher.

2.  **Installation (No external libraries needed):**
    *   No installation is required as this project uses only built-in Python modules (csv).
    *   Simply save the code as a `.py` file (e.g., `student_tracker.py`).

## Build Commands

This project does not require any specific build commands. It's a simple Python script that can be executed directly.

## Functionalities

This command-line application allows you to manage student records.  It provides the following functionalities:

1.  **Add Student Record:**
    *   Prompts the user to enter student details: name, roll number, and marks in three subjects.
    *   Validates input to ensure roll number and marks are numbers.
    *   Stores the data in a dictionary and appends it to a list of student records.

2.  **Display All Records:**
    *   Displays all student records in a formatted way, showing the name, roll number, and marks for each subject.

3.  **Calculate Average Marks:**
    *   Calculates the average marks for each student based on their marks in the three subjects.
    *   Displays the name, roll number, and average marks for each student.

4.  **Save Records to CSV:**
    *   Saves the student records to a CSV file named `student_data.csv`.
    *   Includes a header row with the field names (name, roll\_number, marks1, marks2, marks3).
    *   Handles potential errors during file writing.

5.  **Exit:**
    *   Exits the application.

## How to Run the Application

1.  Open a terminal or command prompt.
2.  Navigate to the directory where you saved the `student_tracker.py` file.
3.  Run the application using the command:

    ```bash  
    python student_tracker.py  
