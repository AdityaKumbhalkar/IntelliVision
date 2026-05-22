# 👁️ IntelliVision

IntelliVision is an AI-powered assistive system designed to help visually impaired individuals navigate and understand their surroundings using real-time object detection and voice feedback.

The system uses YOLOv8 for object detection, OpenCV for real-time video processing, and voice assistance to announce detected objects and scene information.

---

## 🚀 Features

* 🎯 Real-time object detection using YOLOv8
* 🔊 Voice feedback for detected objects
* 📷 Live webcam integration
* 🖥️ Simple and user-friendly GUI
* ⚡ Fast and lightweight processing
* 🧠 AI-powered assistive technology
* ♿ Designed for visually impaired users

---

## 🛠️ Tech Stack

* Python
* YOLOv8
* OpenCV
* PyTorch
* Tkinter
* pyttsx3
* Pillow

---

## 📂 Project Structure

```bash
IntelliVision/
│
├── detector.py
├── speaker.py
├── main.py
├── vision_speak.py
├── webcam_test.py
├── requirements.txt
├── yolov5s.pt
├── yolov8n.pt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/IntelliVision.git
cd IntelliVision
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

Activate the virtual environment:

### Windows

```bash
.\.venv\Scripts\Activate
```

### Linux / Mac

```bash
source .venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install ultralytics opencv-python pyttsx3 pillow torch torchvision torchaudio
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 🧠 How It Works

1. Webcam captures live video feed
2. YOLOv8 detects objects in real-time
3. Detected objects are processed
4. Voice assistant announces detected objects
5. User receives real-time environmental awareness

---

## 📸 Future Improvements

* Face recognition support
* Distance estimation
* Obstacle detection
* Mobile application integration
* Multilingual voice assistant
* GPS navigation assistance

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository and improve the project.

