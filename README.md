# Face_Attendance_System_Project
This project automates daily attendance using face recognition and real-time detection. It captures and logs attendance with accurate time-stamping into a CSV file. By recognizing faces through a webcam and matching them with a pre-trained database, it ensures efficient, reliable, and contactless record-keeping.

Overview:

Developed this project using Python as the core programming language, leveraging OpenCV for real-time face detection and NumPy for efficient numerical operations and image processing. Firstly, used OpenCV to access the webcam and detect faces. For face recognition, used the face_recognition library to compare captured faces with a pre-trained database of known student images.

Once a face was successfully recognized, extracted the current timestamp using Python’s datetime module and logged the student’s name along with the time into a CSV file using Python’s csv module. This created a daily log of attendance in a structured Excel-compatible format.

The project flow includes:
1. Capturing webcam input
2. Detecting and encoding faces
3. Comparing with the known dataset
4. Avoiding duplicate entries using a simple name-check logic
5. Writing recognized names and time to a CSV file in real-time

This setup provided an efficient and fully automated system to track attendance without manual intervention.

Tech Stack Used:
1. Language: Python
2. Libraries & Frameworks:
   a. OpenCV – For real-time face detection using webcam
   b. face_recognition – For encoding and recognizing faces
   c. NumPy – For array and image processing operations
   d. csv – For writing attendance data into Excel-compatible format
   e. datetime – For capturing timestamps

Tools:
1. Webcam (for capturing live video input)
2. VS Code (for development environment)
3. Excel (for checking attendance logs)

