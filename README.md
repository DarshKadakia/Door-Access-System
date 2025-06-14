
# Face Recognition with Excel Logging (No ESP32)

## ✅ Features
- Face recognition using OpenCV
- Excel logging with timestamp and person name
- No hardware (ESP32/buzzer) required

## 🛠 Requirements

### Python:
- opencv-python
- opencv-contrib-python
- openpyxl

Install with:
```
pip install opencv-python opencv-contrib-python openpyxl
```

## 🚀 Setup

1. Add face images in folders inside a `faces/` directory (like `faces/Darsh/`, etc.)
2. Train your model using a training script:
```
python train.py
```
3. Run detection:
```
python detect_and_match.py
```

Detected faces will be logged in `face_log.xlsx`.
