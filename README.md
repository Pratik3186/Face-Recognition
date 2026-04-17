# 🎭 Face Recognition Login System

A desktop-based Face Recognition Authentication System built using Python. This application allows users to log in using their face via webcam and supports registering new users dynamically. 

---

## 🚀 Features

- 📷 Real-time webcam face detection  
- 🔐 Face-based login authentication  
- 🧑 Register new users with face capture  
- 🗂️ Local database storage for user images  
- 📝 Login activity logging with timestamps  
- ⚡ Simple GUI using Tkinter  
- 🌐 Redirect to web page after successful login  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **GUI:** Tkinter  
- **Computer Vision:** OpenCV  
- **Image Processing:** PIL (Pillow)  
- **Face Recognition:** face_recognition library (CLI)  
- **Other Modules:** subprocess, datetime, os, webbrowser  

---

## 📂 Project Structure

```
project/
│
├── main.py                # Main application file
├── util.py                # Utility functions (buttons, labels, etc.)
├── db/                    # Stored user face images
├── tmp.jpg                # Temporary captured image
├── log.txt                # Login logs
└── README.md
```

---

## ⚙️ Installation & Setup guide
  
### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/face-recognition-login.git
cd face-recognition-login
```

---

### 2️⃣ Install Dependencies

```bash
pip install opencv-python pillow face_recognition
```

---

### 3️⃣ Run the Application

```bash
python main.py
```

---

## 🔄 How It Works

1. Webcam captures live video feed  
2. User clicks **Login**  
3. Image is saved temporarily (`tmp.jpg`)  
4. Face recognition compares with stored images in `db/`  
5. If match found → Login success  
6. If not → User prompted to register  
7. Logs are saved in `log.txt` :contentReference[oaicite:0]{index=0}  

---

## 🧑‍💻 Register New User

- Click **Register New User**  
- Capture image from webcam  
- Enter user name  
- Image saved in `db/` folder  

---

## 📸 Key Functionalities

### 🔐 Login System
- Captures current frame  
- Uses CLI-based face recognition  
- Matches against stored dataset  

### 🧾 Logging
- Stores username and login time  
- Helps track system usage  

### 🌐 Web Integration
- Opens GitHub page after successful login  

---

## ⚠️ Requirements

- Webcam device  
- Python 3.x  
- Proper installation of `face_recognition` library  
- Working camera permissions  

---

## 📈 Future Improvements

- 🧠 Replace CLI with direct Python API  
- 📊 Add database (MongoDB / SQLite)  
- 🔒 Add password + face authentication  
- 🌐 Build web version using Django/React  
- 📱 Add mobile support  

---

## 🤝 Contributing

```
Fork → Clone → Create Branch → Commit → Push → Pull Request
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Pratik**  
BTech CSE | Aspiring Developer & Researcher
