# Electronic Advising Transcript

A Java program that helps a student track progress toward graduation requirements, similar to the advising transcript in DePauw's e-Services, but with selectable reports. Built in BlueJ for Computer Science One (Project 3).

## What it does

The `CourseHistory` class reads completed courses from `finishedcourses.txt` into an `ArrayList` of `CompletedCourse` objects. A GUI lets the user pick which report to display:

- **COURSE HISTORY**: all courses in the order they were taken
- **SUMMARY**: total credits earned and GPA (weighted by credit value)
- **DISTAREAS**: completed courses and credits for each distribution area (AH, SS, SM, LA)
- **COMPETENCY**: status of the W, Q, and S competencies
- **FULLREPORT**: summary, distribution areas, and competencies together
- **SORTEDLIST**: all courses sorted by GPA, highest to lowest, without changing the original list

## Concepts practiced

File input, ArrayLists, sorting, code reuse, and writing and documenting a class from scratch.

## How to run

1. Open the project folder in BlueJ.
2. Compile all classes.
3. Right-click `GUIInterface`, choose `new GUIInterface()`, pick a report from the dropdown, and press SUBMIT.

Make sure `finishedcourses.txt` is in the project folder.
