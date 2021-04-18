# Examination_System
A Windows Form application using C# for Examination System 


How to Use It
Steps to go through the system when running:
--------------------------------------------
1- Sign in as student/ instructor 
(each has 3 attempts if inserted wrong password, if attempts exceeded system is closed)

2- IDs and Passwords to try
Student: ID(1) Password(12345)
Instructor: ID(1) Password(DB123)
(for more kindly check the database)

3- Login as instructor first to add an exam 
(insert duration and select on of the courses that this instructor teach, database would be updated in grid)

4- Logout then login as student
(student would only find in the exam list the courses which he is enrolled in that has an exam)

5- Press button to get started 
(a random exam model (if more than 1 exam is created) is generated and random questions are generated)

6- choose the correct answer from the combobox beside each question
(if duration (in minutes) has passed and student didn't submit the button, the exam is submitted and grade reviewed)

7- press submit to get redirected to the grade page

8- you can then choose to log out or go to your profile
(if went back to profile you wouldn't find the exam that has just finished in the exam list)
Tools Used
Windows Form Application C#,SQL Server,ADO
