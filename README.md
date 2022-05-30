# Attendance-system-using-face-recognition

This project is a web-based application demonstrating the use of facial recognition for marking attendance of students built as a part of a mentee challange under [Microsoft Engage-2022](https://acehacker.com/microsoft/engage2022/index.html). It is a web application that can be used by the institue to manage attendance of its students.

## Aim

This project aims to automate the traditional attendance system where the attendance is marked manually. It also enables an organization to maintain its records like in-time and attendance digitally. Digitalization of the system would also help in better visualization of the data using graphs to display the no. of students present today. Its added features serve as an efficient upgrade and replacement over the traditional attendance system.
## Built Using

- **OpenCV** **```(opencv-python==4.4.0.46)```** - Open Source Computer Vision and Machine Learning software library
- **Dlib** - C++ Library containing Machine Learning Algorithms
- **face_recognition** by Adam Geitgey 
- **Django**- Python framework for web development.

## The system mainly works around 2 types of users

1. Student
2. Admin

**Following functionalities can be performed by the admin: <br>**
• Login <br>
• Register new students to the system <br>
• Add students' photos to the training data set <br>
• Train the model <br>
• View attendance report of all students. Attendance can be filtered by date or employee. Attendance graphs representations are also there. <br>

**Following functionalities can be performed by the employee: <br>**
• Login <br>
• Mark his/her time-in by scanning their face <br>
• View attendance report of self <br>
## Face Detection
Dlib's HOG facial detector.

## Facial Landmark Detection
Dlib's 68 point shape predictor

## Extraction of Facial Embeddings
face_recognition by Adam Geitgey

## Classification of Unknown Embedding 
using a Linear SVM (scikit-learn)
## How To Run ?

- clone it on your computer
- make a separate [python virtual environment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) or use the default one already installed on your machine
- Download the zip file of the codes. 
- put it inside a directory
- install the  **``` required libraries and python files inside ```** the directory
- Run **``` python manage.py runserver ```** inside the directory to run the project
- Enjoy !
# Error you may get while running
Please make sure you install **```(opencv-python==4.4.0.46)```** otherwise you may get this error-

<img src="https://user-images.githubusercontent.com/77635325/171044051-92e7628f-24cc-4a14-b488-0406ffa89a18.png" width="60%"></img>

Also make sure there are more than one student's photos are added otherwise it cannot train the data with only one student.


## Learnings from the project

I was quite handy on frontend before the project but not had anything to do with the backend. i used django here of which have seen a tutorial before but first time i applied it on a project. yes it is my first django project and firstly explored the libraries like open-cv and imutils and also the database management of django itself which is done by sqlite3. i was having so difficulties at first dealing with the face-recognition part. it took more than a week for implementing the recognition models and come out with the clustering technique with face_recognition library and classified with the Linear SVM by sk-learn. Then there comes the web development part which firstly had a lot of planning that what functions it should have and all. But i worked with django and bootstrab + HTML and by searching on google itself i debug the things like moduleError and integration errors and others.
- I have documented the project in the report which link has been given below.

## Documentation 
[Link To folder](https://github.com/Hemant-25/Attendance-system-using-face-recognition/tree/main/Documents)
- [Link to report](https://drive.google.com/file/d/1mFEmeVgzLJCfbxvlOmQso7xb_8MmyUOj/view?usp=sharing)
## UI screenshots

<img src="https://user-images.githubusercontent.com/77635325/170841450-e361aaf5-9ae4-4190-ad63-c5a8081b81c1.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841454-0f7a447a-dca8-4980-a239-0239c1baa41a.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841476-f5b2a7d9-4c70-4ec1-9d11-1045e9c0b3b0.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841479-dcc417b1-fffd-43b3-bfa5-2912bb739524.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841481-56b71a78-a457-4a37-a859-be1523354b94.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841489-fac434f7-4917-417e-8239-d87933c3e7f9.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841490-94b228b9-bd07-479d-b7fa-54e94ff79733.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841510-06b971e3-1cc4-4ca8-a8a2-ac95a9bf8bb4.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841515-344d9d5c-54d5-4fde-be07-143209ed43ac.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841517-bad9c55f-82f6-4e08-9c3f-5641d32bced7.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841519-005bf465-8921-45e0-a6f1-da0e95ee0fa3.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841520-6010f23e-3dfc-413b-83e5-7dc880b12580.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841527-14a15872-7efe-4043-a6d5-1555f5fc2726.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841522-a3bbed82-1580-4df5-b33d-bde66db43940.png" width="45%"></img>
<img src="https://user-images.githubusercontent.com/77635325/170841529-67cdcdea-6285-4c00-a5e1-055a1fcbf6e2.png" width=45%></img>
<img src="https://user-images.githubusercontent.com/77635325/170841530-4a7af450-151c-49e4-a5c5-c11b3f0e2da0.png" width="45%"></img>

# Thank You
