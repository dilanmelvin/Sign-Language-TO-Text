# Sign Language to Text Converter

## 📝 Project Description

This project translates sign language gestures into text using computer vision and a pre-trained Convolutional Neural Network (CNN). It leverages OpenCV and TensorFlow to process webcam input, predict the gesture shown, and display the recognized text.

---

## 🧰 Tech Stack

* Python 3.x
* OpenCV
* TensorFlow / Keras
* cvzone

---

## 🚀 Installation & Setup

### 1. Clone the repository

```
git clone <your-repo-link>
cd Sign-Language-TO-Text
```

### 2. Create a virtual environment

```
python -m venv venv
```

### 3. Activate the environment

**For Windows Command Prompt:**

```
venv\Scripts\activate
```

**For PowerShell:**

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\venv\Scripts\Activate
```

### 4. Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Running the Application

### Without GUI (Simple Prediction)

```
python prediction_wo_gui.py
```

### With GUI or Full Webcam Prediction

```
python final_pred.py
```

### To Collect New Data (Optional)

```
python data_collection_final.py
```

---

## 📁 Files Description

* `cnn8grps_rad1_model.h5` – Pre-trained model for gesture recognition
* `prediction_wo_gui.py` – Predicts signs from webcam without GUI
* `final_pred.py` – Predicts signs with GUI and advanced features
* `data_collection_final.py` – Script to collect new gesture data
* `requirements.txt` – Python dependencies

---

## 📷 Notes

* Ensure webcam is connected
* If you encounter errors, check for missing modules and install them using `pip`

---

## ✅ Status

Project is functional and tested with pre-trained model.

Feel free to improve the model or extend the gesture set!
