# 🧍 PosturePro
### Real-Time Fall Detection with Offline Voice Alert — Edge Deployed

# 📌Overview:
Falls are a leading cause of injury-related mortality among elderly, yet existing wearable sensors suffer from poor user compliance and
cloud-based vision systems demand constant internet — making them impractical in rural and resource-limited environments.

PosturePro is a fully offline, camera-based fall detection system running entirely on Raspberry Pi 4B. It detects falls using MediaPipe
pose estimation with Kalman filtering and multi-signal voting, triggers a local buzzer alert cancellable by voice command, and instantly
notifies emergency contacts via GSM SMS — no wearables, no internet, no cloud, just plug and protect.

## 🎯 Objectives
- Fall Detection
- Audio Alert
- Voice Cancellation
- SMS Alert
- Edge Deployment

## ✨ Features
- 🦴 **Pose Estimation** — MediaPipe with 33 body landmarks
- 📊 **Keypoint Smoothing** — Kalman filter for stable tracking
- 🗳️ **Fall Classifier** — Multi-signal voting (torso angle, hip position, SAR, hip joint angle)
- 🔔 **Smart Alert** — Periodic beep-silence pattern (2s ON / 5s OFF)
- 🎙️ **Voice Cancellation** — Offline Vosk speech recognition to cancel false alarms
- 📱 **SMS Alert** — GSM SIM800L notifies 3 emergency contacts instantly
- 🌐 **Fully Offline** — No internet, no cloud, edge deployed on Raspberry Pi
  
## Software:
>* Python 3.9
>* MediaPipe 0.10.14
>* OpenCV 4.8.0
>* NumPy 1.24.3
>* Vosk 0.3.45
>* SoundDevice 0.4.6
>* WebRTCVAD 2.0.10
>* PySerial 3.5
>* RPi.GPIO 0.7.0

## Hardware:
>1.Raspberry Pi 4B -  2GB+ RAM

>2.MicroSD Card - 32GB (OS + project files)

>3.MicroSD Card Reader - To flash Raspberry Pi OS

>4.USB Webcam

>5.USB Microphone

>6.Active Piezoelectric Buzzer(3.3v) 

>7.SIM800L GSM Module 

>8.Any 2G SIM

>9.10µF 25V Capacitor

>10.1kΩ Resistor -1, 2kΩ Resistor-1

>11.5V-5A adapter - Power Source

# Test Runs: 
<img width="588" height="437" alt="Screenshot 2026-05-13 215636" src="https://github.com/user-attachments/assets/97fcf26c-df0c-40bc-814f-8e1b86e56619" />
<img width="586" height="439" alt="Screenshot 2026-05-13 215815" src="https://github.com/user-attachments/assets/b20eb493-fc13-4c6e-9ba6-a74dbbaf67b2" />
<img width="589" height="439" alt="Screenshot 2026-05-13 215924" src="https://github.com/user-attachments/assets/68e6ba04-9400-495f-bc73-9290cd543de8" />
<img width="591" height="441" alt="Screenshot 2026-05-13 220002" src="https://github.com/user-attachments/assets/90eb8f39-f836-485c-8d2c-69e67eea7012" />

## Project References:
[1] Lugaresi et al., MediaPipe: A Framework for Building Perception Pipelines 
[MediaPipe A Framework for Building Perception Pipelines.pdf](https://github.com/user-attachments/files/27718953/MediaPipe.A.Framework.for.Building.Perception.Pipelines.pdf)

[2] Min et al., Human Fall Detection Using Normalized Shape Aspect Ratio 
[Combined curvelets and hidden Markov models.pdf](https://github.com/user-attachments/files/27719049/Combined.curvelets.and.hidden.Markov.models.pdf)

[3] Kalman, A New Approach to Linear Filtering and Prediction Problems
[Kalman Filter Based Elderly Fall Detection with a Triaxial Accelerometer.pdf](https://github.com/user-attachments/files/27719067/Kalman.Filter.Based.Elderly.Fall.Detection.with.a.Triaxial.Accelerometer.pdf)

