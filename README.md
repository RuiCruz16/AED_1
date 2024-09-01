# AED-Project-1-Schedule

This project was carried out in the **second year, first semester** of the course, where we had to implement a school schedule management system using linear data structures.

## Overview

In this project, we developed a system in **C++** to manage school schedules, allowing the manipulation of information related to students, classes, curricular units (UCs), and schedule change requests. The system was designed to facilitate the visualization and modification of student schedules, as well as the processing of requests for class or UC changes, enrollments, and UC removals.

## Features

### Key Features

- **Student Management**

  - Loads and stores information about students and their respective classes.
  - Displays detailed information about students by academic year, number of UCs, and their respective classes.

- **Schedule Management**

  - Displays schedules for classes, curricular units, and students.
  - Checks for schedule conflicts and class capacity for making changes.

- **Request Processing**

  - Generates and processes requests for class changes, UC changes, enrollments, and UC removals.
  - Balances classes after changes are made, maintaining an even distribution of students.

- **Maintenance and History**
  - Stores and processes rejected and approved requests, allowing for review and rollback of changes when necessary.
  - Automatically updates records in CSV files after requests are confirmed.
