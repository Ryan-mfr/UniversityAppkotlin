# UniversityAppkotlin
An E-learning mobile Application using Kotlin Language and Firebase database
University Mobile App- Education App

Simple Education app created with Kotlin and Google Firebase.

Table of Contents

-General Info
-Technologies
-Setup
-Database

General Info:

This project is a simple education education mobile application.

Functionalities/ features: 

-Student log in/ log out(with validation)
-Student view all events organised by the University through the event tab.
-Student update their details through the profile tab(Firstname and lastname)
-Student choose the course he/she wants to view the information about.
-Student comments/ chat on the comments/group chat page of the specific course.
-Student downloads files posted by lecturers(Notes, Homeworks and Assignments)
-Lecturer logs in/ log out(validation)
-Lecturer adds or removes notes
-Lecturer adds or removes homeworks
-Lecturer posts submission dates
-Lecturer posts comments/ chat in the specific group chat
-Comments cannot be removed due to diciplinary rules.
-Submission dates cannot be removed.
-Auto-Login if the user has not logged out last time he/she has used the app.
-Safe Log-out(No access even on back press).
-Student views their student time table by clicking on textView provided in app.
-Student views their results by clicking on textView provided in app.
-Password reset through email.
-Tabular view.
-Push notification on comment.
-Student view submission dates.
-Course-wise app.
-3 level of control over app: admin, student, tutor.

Technologies:

Android Studio 4.2.1
Build #AI-202.7660.26.42.7351085
Gradle version: 7.0.2
Kotlin version: 1.5.10
SDK version: 31

Runtime version: 11.0.8+10-b944.6842174 amd64
VM: OpenJDK 64-Bit Server VM by N/A

Setup:

-Extract the apk file and send it to an android device.
-Make sure the device has enough storage and provided with a stable internet connection.
-Enable install apps from unknown sources temporarily(if needed).
-Install the app and you are good to do!


Login:

-Create a project in firebase and download the json file then paste it in the project file.
-Create users using authentication library in Firebase.
-Enter the usertype in firebase firestore. (usertype: Students | Tutor)


Database:

Google Firebase:
	Authentication
	Realtime Database
	Cloud Storage
	
Database name: universityapp-a2800

status: active

Demo: https://youtu.be/6AX1G29Nvas
