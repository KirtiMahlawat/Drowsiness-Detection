# Drowsiness Detection System 😴🚗

This project aims to detect drowsiness in individuals using real-time webcam footage by analyzing facial landmarks, especially focusing on eye aspect ratio (EAR). It alerts the user when signs of drowsiness are detected.

---

## 🔍 Features

- Real-time detection using webcam
- Facial landmark detection with Dlib
- Eye Aspect Ratio (EAR) based logic
- Audio alert on drowsiness detection
- Simple and easy-to-understand codebase

---

## 📂 Project Structure

```
Drowsiness-Detection/
│
├── models/
│   └── shape_predictor_68_face_landmarks.dat   ← Required pre-trained model
│
├── drowsiness_detection.py                     ← Main script
├── README.md                                   ← You're here!
└── requirements.txt                            ← Python dependencies
```

---

## 📥 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/KirtiMahlawat/Drowsiness-Detection.git
cd Drowsiness-Detection
```

### 2. Download the required model

- Download the `shape_predictor_68_face_landmarks.dat` file from this [Kaggle link](https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat/code)
- Place the downloaded `.dat` file inside the `models/` folder

### 3. Install the dependencies

It's recommended to use a virtual environment.

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

Make sure your webcam is connected.

```bash
python drowsiness_detection.py
```

Once the program starts:
- It will begin capturing video.
- If it detects drowsiness (i.e., eyes remain closed for a threshold duration), it will play an alarm.

---

## 🛠 Dependencies

- Python 3.x
- OpenCV
- Dlib
- Imutils
- Playsound (or similar for alert)

All dependencies are listed in `requirements.txt`.

---

## 👩‍💻 Author

**Kirti Mahlawat**  
[GitHub Profile](https://github.com/KirtiMahlawat)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
