# Student Course Registration Form

A simple and interactive web-based form that allows students to enroll in various tech courses.This Project built using HTML, CSS, and JavaScript. This includes real-time age calculation, email validation, dynamic course fee display. The app stores data in the browser's localStorage and displays registered students in a separate view.


## 🔗 Demo Flow
- Student fills out the registration form (index.html).
- Data is saved to browser's localStorage.
- Clicking "View Registered Students" opens students.html, which reads and displays all student records.

## ✨ Features
- ✅ Student Name & Email Validation
- 📅 Automatic Age Calculation from birthdate
- 💰 Dynamic Course Fee Display based on selected course
- 🧠 Form Data Stored in Browser using localStorage
- 🧼 Form Reset & Input Validation after successful enrollment

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript

## How to Use
1. Clone the Repository
- git clone https://github.com/pranali040/Course-Registration-Form.git 
- cd student-registration

2. Open with Live Server (Recommended)
- Make sure you do not open via file:///, which may block localStorage in some browsers.
- Use VS Code with the Live Server extension: Right-click index.html → Open with Live Server

3. Register a Student
- Fill the form on index.html
- Click "Enroll to Course"
- Success alert will confirm registration

4. View Registered Students
- Click the "View Registered Students" link
- students.html will display all students in a table

## Screenshot

1. Course Registration Form - Student Input Page
   
![image](https://github.com/user-attachments/assets/db3dc9b3-9c00-46b8-8780-a0c88a885a4d)

2. Registered Student Displayed in Table
   
![image](https://github.com/user-attachments/assets/0ce2071a-9139-4e8b-a87a-9687bfda125d)

## 🧪 Validation Rules
1. Name: Must contain only letters and spaces.
2. Email: Must follow standard email format.
3. Age: Automatically calculated and must be non-negative.
4. Course Fee: Automatically populated from course selection.

## 📌 Notes
- Age is calculated dynamically using the birthdate
- Fee updates automatically based on course selection
- Entries persist unless cleared from browser storage

## 🧹 To Clear All Student Data
Open browser DevTools → Application tab → Local Storage → Right-click → Clear
