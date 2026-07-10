# Student Enrollment Form - JsonPowerDB

## Table of Contents
- [Description](#description)
- [Illustrations](#illustrations)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Scope of functionalities](#scope-of-functionalities)
- [Examples of use](#examples-of-use)
- [Project status](#project-status)
- [Release History](#release-history)
- [Sources](#sources)
- [Other information](#other-information)

---

## Description
This project is a highly interactive, serverless web-based "Student Enrollment Form" developed as a Micro Project for the "Introduction to JsonPowerDB - V2.0" course by Login2Xplore. It provides a frontend interface built with HTML and Bootstrap that connects directly to JsonPowerDB (JPDB) using AJAX. The application stores and retrieves data from the `STUDENT-TABLE` relation of the `SCHOOL-DB` database without the need for any traditional backend server.

## Illustrations

<img width="696" height="373" alt="image" src="https://github.com/user-attachments/assets/c1cf0b00-b22b-4ab5-9bba-c6b1844e173f" />

## Benefits of using JsonPowerDB
- **Serverless & Schema-free:** Simplifies development by acting as a nimble, in-memory database.
- **Fast Development:** Eliminates the need for backend coding, significantly reducing development time and cost.
- **Multi-Mode Database:** Functions seamlessly as a Key-Value, Document, or Relational database depending on the requirement.
- **REST API Integration:** Allows easy data retrieval and storage in JSON format using simple API calls.
- **High Performance:** Built on top of highly efficient data engines for real-time web applications.

## Scope of functionalities
- **Primary Key Validation:** Automatically checks the database when a user inputs a Roll Number.
- **Insert New Data:** Unlocks the form for data entry and saves new student details if the Roll Number is unique.
- **Update Existing Data:** Automatically retrieves and displays existing student data for editing and updates it in the database.
- **Dynamic UI Control:** Form fields and action buttons (Save, Update, Reset) dynamically enable or disable based on database responses to prevent data entry errors.
- **Reset Functionality:** Quickly clears the form to its default, secure state.

## Examples of use
1. **Starting the Form:** Open the webpage. Only the 'Roll No.' field will be active.
2. **Adding a Student:** Enter a new Roll Number (e.g., `101`). The form will unlock. Fill in the Full Name, Class, Birth Date, Address, and Enrollment Date, then click the **Save** button.
3. **Updating a Student:** Enter an existing Roll Number (e.g., `101`). The form will automatically populate with that student's saved data. Edit the required fields (e.g., change the Class or Address) and click the **Update** button.
4. **Clearing the Form:** Click the **Reset** button at any point to clear all fields and start over.

## Project status
**Completed:** Version 1.0.0 is finished and successfully fulfills all the micro-project requirements set by the course.

## Release History
- **v1.0.0**
  - First official release of the JPDB integrated project on GitHub.
  - Added UI with HTML5 and Bootstrap 3.
  - Integrated `jpdb-commons.js` for database connection.
  - Successfully implemented GET, PUT, and UPDATE functionalities.

## Sources
- **Database Provider:** [JsonPowerDB by Login2Xplore](https://login2explore.com/)
- **UI Framework:** [Bootstrap](https://getbootstrap.com/docs/3.4/)
- **Icons & Scripts:** jQuery and JPDB Commons JS.

## Other information
- **Author:** Humna Ahmed
- **Course:** Introduction to JsonPowerDB - V2.0
- **License:** MIT License
