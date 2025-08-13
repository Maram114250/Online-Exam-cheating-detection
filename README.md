# Online-Exam-cheating-detection
# AI-Based Exam Cheating Detection

A real-time **AI-powered exam monitoring application** built using **Python, OpenCV, MediaPipe, YOLOv8, and Streamlit**.  
The system detects **students’ face movements, absence, presence of multiple faces, and forbidden actions** during an exam. It also plays alert sounds when suspicious behavior is detected, making it ideal for **online or computer-based testing environments**.  

## 🚀 Features  

- **Real-time face tracking** with MediaPipe.  
- **YOLOv8 object detection** for identifying suspicious objects or behaviors.  
- **Alerts & sounds** for detected violations.  
- **Multi-threaded camera handling** for smooth performance.  
- **Fallback mode** if YOLO model is unavailable.  
- **Streamlit web interface** with custom CSS for better UI/UX.  

---

## 🛠️ Tech Stack  

- **Programming Language:** Python 3.x  
- **Frameworks & Libraries:**  
  - [Streamlit](https://streamlit.io/) – Web interface  
  - [OpenCV](https://opencv.org/) – Video processing  
  - [MediaPipe](https://developers.google.com/mediapipe) – Face detection  
  - [YOLOv8 (Ultralytics)](https://github.com/ultralytics/ultralytics) – Object detection  
  - [Pygame](https://www.pygame.org/) – Sound alerts  

---

## 📂 Project Structure  

```
📁 Exam-cheating-detection
│── main.py                # Main application file  
│── yolov8n.pt              # YOLO model 
│── requirements.txt       # Dependencies  
│── README.md              # Documentation  
```

---

## 📦 Installation  

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/NASO7Y/Exam-cheating-detection.git
```

2️⃣ **Create and activate virtual environment**  
```bash
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate     # On Windows
```

3️⃣ **Install dependencies**  
```bash
pip install -r requirements.txt
```

4️⃣ **Download YOLOv8 model (optional)**  
```bash
wget https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt
```

---

## ▶️ Usage  

Run the application locally:  
```bash
streamlit run main.py
```

- **Start Camera** – Begin monitoring the exam.  
- **Stop Camera** – End monitoring session.  
- **View Violations** – Check logs of suspicious activities.  

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.


---

## 📌 Future Improvements  

- Add **eye gaze tracking** to detect cheating more accurately.  
- Support **multiple camera feeds** for classroom settings.  
- Store **violation history** in a database.  
- Deploy as a **cloud-based service** with remote proctoring dashboard.  


---

## 👥 Authors

- [Maram114250](https://github.com/Maram114250)  
- [Ahmed Noshy](https://github.com/NASO7Y)  


