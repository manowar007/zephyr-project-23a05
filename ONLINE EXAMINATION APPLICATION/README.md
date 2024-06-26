# MANOWAR GHANI, MCA 4th SEM,COTTON UNIVERSITY

# TOPIC- ONLINE EXAMINATION APPLICATIONS

OEA is a system that helps institutes provide their students with an online exam platform. The system has two types of users which are the Admin and the Students/Examinee.

The Admin user will be using the admin panel of the system that they are in charge of populating and maintaining the system’s data. They will manage the list of Courses, Exams, Exam Questionnaires, and Examinees. The admin user can view the exam results and feedback of the students.

The Student Users can only take the exam, view their results, and send feedback to the admin. Talking about the student taking the exam, the exam will only be created with a limited time duration. Every student who will start to take the exam will only be allowed to finish answering that by the given period.

It may be used as a tool  to overcome the limitation of traditional pen and paper examinations.

# MODULES OF THE PROPOSED SYSTEM:

 It consists of two main modules:
 Admin 
 Student
 
 ADMIN MODULE:
 SCREENSHOT OF ADMIN MODULE: ![Screenshot 2024-05-28 224603](https://github.com/zephyr-internships-23a/zephyr-project-23a05/assets/154730401/a4cd83e4-0c50-455d-8882-8855deb1dd65)
 Login: In this module, the admin is granted access to the system on providing a valid credential.
 
 Manage Courses: This module helps the admin in managing the courses. The admin can add new courses or delete courses that are not required for the exams.
 
 Manage Exams: This module helps the admin to manage the exam. For example: the title of the exam, the course on which the exam will be held, time limit. It can also delete the exam from the database.
 
 Manage Exam’s Questionnaire: This module helps the admin in creating questions for a given exam. The questions can be based on Multiple Choice Questions. The admins can also edit, update, and delete the questions. 
 
 Manage Examinees: This module helps the admin manage the users who appear for the exams by accepting credentials like usernames and passwords.
 
 View Examinee Results: This module helps the admin to check results by evaluating quickly and accurately based on the correct number of answers scored by the user.
 Read Feedback: This module allows the admin to read feedback provided by the examinee.
 
 STUDENT MODULE:
 SCREENSHOT OF STUDENT MODULE: ![Screenshot 2024-05-28 225329](https://github.com/zephyr-internships-23a/zephyr-project-23a05/assets/154730401/5844f612-f651-4055-84d3-fd55d2be5cb3)

 
 Login: In this module, the student is granted access to the system on providing a valid credential.
 
 Take the Exams: This module helps the student/examinee to check for available exams. If an exam is available then he/she can take the exam and complete it within the given time sequence. After taking the exam the examinee has to click on the submit button to submit the exam.
 
 View their Results: This module helps the student/examinee to check for the results in which they have appeared as well as previous exam results.
 
 Send Feedback: This module helps the student/examinee to send feedback to the admin/faculty like how was the exam, or how smooth was the online exam conducted.

 # LIMITATIONS:

 -It has no real existence in internet just tested on localhost.

 -The question is not displayed randomly.

 -There is no negative marking and there is no fixed time and date for online exam, It can lead to excessive cheating. 

 -Not suitable for collaborative evaluations or group project. 

 -There are subject like mathematics, economic, science, that are difficult to attempt online as include formulae.

 -In case of any type of problem in student verification no functionality is define in a system to correct it or intercommunication among user are also not available. 

 -Online examination system is restricted to multiple choice question which can be inefficient in assessing a student’s topic Mastery. Exams in the form of debates, essays, case-based questions and oral exams are difficult to conduct online. 

 -Online examination system does not support for adding images with question so questions containing diagram can not be saved in the system. 

# INSTRUCTION ON HOW TO RUN THE PROJECT LOCALLY

-Clone the repository and open the folder named ONLINE EXAMINATION APPLICATION in VS CODE and save the file.

-Now copy the folder from the saved path and paste it in the htdocs folder in the Xampp folder.

-(To connect the Database)

1.open xampp control panel and then click on start Apache and start MySql, then click on the admin button of mySQl which will direct to a brower. After that click on the new database tab in the browser window .

2. Now create a new database named cee_db and then click on create button. Then click on the import tab, this will open the browse file. From the browse file click on htdocs>ONLINE EXAMINATION APPLICATION>database>cee_db.sql and then click on import/go option.

-After creating and importing the database go to any browser and type localhost/ONLINE EXAMINATION APPLICATION/adminpanel/admin to check the admin dashboard

to login in for admin

username- admin@username

password- admin@password

type the URL localhost/ONLINE EXAMINATION APPLICATION to check the student module
to login for student- You can choose any of the students credentials stored in the manage examinee module in the admin dashboard
for eg- 

username- monu@gmail.com

passowrd- monu111

(Important- Keep on running the apache and MySql server from the Xampp Control panel to run the application in localhost)

# TECH USED FOR DESIGNING:

-	Front End technology- HTML, CSS, Javascript, Bootstrap, AJAX
  
-	Backend Technology- PHP, MySQL
  
-	Database: MySQL
  
-	Server: Apache Server

-	Software used to run the system locally- Xampp

# FUTURE SCOPE:

Developments in software technology are continuing dynamically. This has forced developers to look for new approaches to look for new approaches to design and develop. In order to face this situation, the modules in a system should be updated anytime. The modules in this system can be subjected to further enhancements, such as:

-Development discussion forums.

-Implementation on cloud server.

-Multimedia feature supports.

-Integrate learning materials.

-Integrate a registration form for the user.


 
 
 
 
 
 
 
  

