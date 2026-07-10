# Student Enrollment Form - JsonPowerDB Micro Project

> A minimal and interactive web-based Student Enrollment Form using HTML, Bootstrap, and JsonPowerDB (JPDB) for serverless database operations.

## 📸 Screenshots

<img width="696" height="373" alt="image" src="https://github.com/user-attachments/assets/c1cf0b00-b22b-4ab5-9bba-c6b1844e173f" />


## 📝 Description

This is a micro project for the "Introduction to JsonPowerDB - V2.0" course provided by Login2Xplore. It demonstrates how to create a highly responsive web form to perform Insert and Update operations directly to a database without needing a backend server. 

The application takes input for a student and stores the data in the `STUDENT-TABLE` relation of the `SCHOOL-DB` database. It utilizes AJAX calls to communicate with the JsonPowerDB REST APIs.

## 🚀 Benefits of using JsonPowerDB

* **Serverless & Schema-free:** It is extremely simple to use, nimble, and acts as an in-memory database.
* **Fast Development:** Helps developers in faster coding, which in turn reduces development cost and time.
* **Multiple Uses:** Can be used as a Key-Value, Document, or Relational database depending on the requirement.
* **Easy Integration:** Simplest way to retrieve data in a JSON format using Rest API.
* **High Performance:** Built on top of one of the fastest and highly efficient data engines.

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, Bootstrap (v3.4.1)
* **Backend/Database:** JsonPowerDB
* **Scripting:** JavaScript, jQuery, `jpdb-commons.js`

## 💡 How to Use

1. Clone this repository or download the `index.html` file.
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, etc.).
3. The cursor will automatically focus on the **Roll No.** field. Enter a Roll Number:
   * **New Record:** If the Roll Number does not exist, the form will enable the rest of the fields. Fill in the details (Name, Class, Birth Date, Address, Enrollment Date) and click **Save**.
   * **Existing Record:** If the Roll Number is already in the database, the form will automatically fetch and display the existing data. You can modify the fields and click **Update**.
4. Use the **Reset** button at any time to clear the form and start over.

## 📅 Release History

* **v1.0.0** (Current)
  * Initial release containing basic UI with HTML/Bootstrap.
  * Integration of JPDB for GET, PUT, and UPDATE functionalities.
  * Form validation and dynamic button controls implemented.

## 👤 Meta

**Humna Ahmed** Distributed under the MIT license. Feel free to use and modify the code.

[https://github.com/HumnaAhmed/Student-Enrollment-JPDB](https://github.com/HumnaAhmed/Student-Enrollment-JPDB)
