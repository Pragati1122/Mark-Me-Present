# Mark-Me-Present (Facial Recognition)

Mark-Me-Present is basically a students' record management, Tkinter based GUI-application. It records the details of the students in a database and also helps to record their attendance through Facial Recognition.
It records the real-time video of a person and reognizes their face. The identity of the person is then sent to the attendance records.

## Tech Stacks and Algorithms Used:
1. Python
2. OpenCV
3. MySQL
4. Haarcascade Opencv (Object Detection)
5. LBPH Opencv (Face Recognition)
6. Tkinter


### The homepage of the application provides six features namely:
1. Student Portal - Maintains the personal and academic details of the students through MySQL as a database.
2. Face Detector - Captures the face of a person through webcam and recognizes it. Helps to maintain the attendance.
3. Photos - Stores the images of the people whose face has already been fed in the system.
4. Train Data - This option helps to train the images stored in Photos folder so that it can be recognized.
5. Attendance - This option maintains precise attendance records of the students in the form of csv files. We can also export those csv files.
6. Exit - Option to exit the application.


To execute this repository, please follow these steps:
1. Clone this repository to your local system.
2. Install all the required packages if not already.
3. Run the command- python main.py
