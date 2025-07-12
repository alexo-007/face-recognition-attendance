# Face Recognition Attendance System

The **Face Recognition Attendance System** is a desktop-based GUI application that uses facial recognition technology to automate the process of student attendance. This system captures a student's face using a webcam and marks their attendance if their face is recognized from previously trained data. The system also supports email notifications to parents and voice announcements for each successful recognition.

---

## ✨ Features

- GUI-based interface using Tkinter.
- Student registration with image capture.
- Face recognition using OpenCV and Haar Cascade.
- Attendance recording and CSV logging.
- Email notifications sent to parents when a student is marked present.
- Audio announcement using Google Text-to-Speech (gTTS).
- Password protection for profile saving.

---

## 💻 Tech Stack

- **Language**: Python 3
- **Libraries**: OpenCV, NumPy, Pandas, PIL, Tkinter, gTTS, playsound, smtplib

---

## 📦 Requirements

All required Python libraries are included in the `requirements.txt` file. Install them using:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Step 1: Install Python

Download and install Python from the official site:  
👉 https://www.python.org/downloads/

### Step 2: Unzip the Project Folder

Unzip the project folder (which will contain all required files including the Haar Cascade file, `requirements.txt`, password file, and training folders).

### Step 3: Install Required Libraries

Open CMD or Terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### Step 4: Run the Project

```bash
python main.py
```

---

## 📧 Email Notifications

To enable email notifications, replace:
- `sender_email`
- `sender_password` (use App Passwords if using Gmail)

---

## 📁 Folder Structure

```
.
├── Attendance/
├── StudentDetails/
├── TrainingImage/
├── TrainingImageLabel/
├── haarcascade_frontalface_default.xml
├── requirements.txt
└── your_script.py
```

---

## 🔐 Default Password

To save a student's profile, you will be prompted to enter a password.  
The password is stored in the `psd.txt` file inside the `TrainingImageLabel/` folder.  
If not found, you will be asked to set a new one.  
**Default password**: `smagix`

---

## 📬 Contact

For any support, contact: **alexovellatiparambill@gmail.com**