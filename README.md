# 🧠 Brain–Computer Interface (BCI) Project

A real-time Brain–Computer Interface system designed to interpret EEG signals and classify user attention states using machine learning, enabling interaction with a mind-controlled application.

---

## 📌 Overview

This project focuses on processing real-time EEG (Electroencephalography) signals to detect attention levels and translate them into actionable outputs for an interactive system. The application demonstrates how neural signals can be converted into meaningful control signals using signal processing and machine learning techniques.

Due to hardware and lab environment dependencies, only selected snippets and demonstration visuals of the project are shared in this repository.

---

## ⚙️ Tech Stack

- Python  
- Lab Streaming Layer (LSL)  
- NumPy  
- Scikit-learn  
- Signal Processing Techniques  
- Machine Learning (SVM)

---

## 🚀 Features

- Real-time EEG signal acquisition using Lab Streaming Layer
- Signal preprocessing including filtering and normalization
- Feature extraction from EEG frequency bands
- Attention-state classification using Support Vector Machine (SVM)
- Integration with an interactive mind-controlled game
- Real-time prediction and feedback loop

---

## 🧩 Repository Contents

This repository includes:

- Key implementation snippets
- Core logic demonstrations
- Output visuals/screenshots
- Conceptual workflow references

The full implementation requires:

- EEG acquisition hardware
- Lab-specific configuration
- Device drivers and proprietary SDK access

Hence, only non-restricted parts are publicly shared.

---

## 🧠 How It Works (Conceptual Flow)

1. EEG signals are captured from sensors.
2. Data is streamed in real time via LSL.
3. Signals undergo preprocessing:
   - Noise filtering
   - Normalization
4. Feature extraction is performed.
5. Extracted features are fed into an SVM classifier.
6. Model predicts attention state.
7. Prediction drives interaction in the application.

---

## 📊 Results

The system successfully classified attention states in real time and enabled responsive interaction within the mind-controlled environment.

---

## ⚠️ Note on Code Availability

The complete project cannot be fully open-sourced because it depends on specialized EEG hardware and lab-specific infrastructure. This repository serves as a conceptual and implementation reference showcasing the methodology, architecture, and selected implementation components.

---

## 🔮 Future Improvements

- Deep learning–based EEG classification
- Improved signal noise reduction
- Cross-user calibration
- Portable hardware integration
- Expanded real-time applications

---

## 👩‍💻 Author

**Ananya Saxena**

- GitHub: https://github.com/Ananyasaxena26
- LinkedIn: https://www.linkedin.com/in/ananya-saxena-81b171285/

---

## ⭐ Acknowledgment

This project was developed in a Brain–Computer Interface lab environment with access to EEG acquisition hardware and supervised experimentation facilities.
