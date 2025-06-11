📌 Face Recognition Attendance System
A Final Year Project (FYP) developed using Python to automate attendance marking through face recognition.

📂 Project Structure
bash
Copy
Edit
Python-FYP-Face-Recognition-Attendence-System-master/
├── attendance.py                  # Marks attendance via face recognition
├── face_recognition.py           # Handles the core recognition logic
├── main.py                       # Main GUI entry point
├── login.py                      # Login functionality
├── developer.py                  # Developer info module
├── helpsupport.py                # Help and support module
├── databaseTest.py               # Database testing
├── clf.xml                       # Trained classifier model
├── haarcascade_frontalface_default.xml  # Haar cascade for face detection
├── abc.csv / attendance.csv      # Attendance records
├── *.log / *.txt                 # Log and error tracking
├── .gitignore
🚀 Features
🎯 Real-time face recognition for attendance

📷 Uses OpenCV and Haar cascades

🔐 Secure login system

📊 Attendance stored in CSV files

🛠 Admin/developer interface and help section

🛠 Technologies Used
Python 3

OpenCV

Tkinter (for GUI)

NumPy

Pandas

▶️ How to Run
Install Dependencies:

bash
Copy
Edit
pip install opencv-python numpy pandas
Run the Application:

bash
Copy
Edit
python main.py
Other Utilities:

attendance.py: Marks attendance based on live recognition.

databaseTest.py: Test database connectivity or operations.

login.py: Handles login UI.

📁 Dataset/Model
clf.xml is a trained face recognition model (likely via LBPH).

haarcascade_frontalface_default.xml used for detecting faces.

🧑‍💻 Developer
Developed as part of a Final Year Project for automating institutional attendance systems.  
