# Heart Rate Measurement using Camera 📸❤️

This project demonstrates how to measure a user's heart rate using a standard webcam by analyzing subtle changes in facial skin tone caused by blood flow. It uses computer vision and signal processing techniques to estimate pulse rate in real-time.

---

## 🚀 Features

- Real-time heart rate monitoring using webcam
- Face detection and tracking
- Region of interest (ROI) extraction from forehead or cheeks
- Signal extraction using photoplethysmography (PPG) principles
- Frequency analysis using Fast Fourier Transform (FFT)
- BPM (Beats Per Minute) calculation and display

---

## 📸 How It Works

1. Captures live video feed using the webcam.
2. Detects the face and selects a region of interest (ROI).
3. Analyzes the subtle color variations due to blood flow.
4. Applies Fast Fourier Transform (FFT) to the signal to find the dominant frequency.
5. Converts the frequency into Beats Per Minute (BPM).

---

## 🛠️ Technologies Used

- Python 3.x
- OpenCV
- NumPy
- SciPy
- Dlib / Mediapipe (for face detection and tracking)
- Matplotlib (optional, for visualizing signals)

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/Heart-Rate-Measurement-using-camera.git
cd Heart-Rate-Measurement-using-camera
