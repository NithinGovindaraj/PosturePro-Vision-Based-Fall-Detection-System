# Sem -3; PosturePro
Posture Pro is a Vision-Based Real-Time Fall Detection Using Pose Estimation with Offline Voice-Activated Alert Cancellation for Edge Deployment

# Overview:



## Objectives
- Real-Time Monitoring
- SMS Alert
- Offline Connectivity

## Features
- MediaPipe Pose estimation (33 landmarks)
- Kalman filter for keypoint smoothing
- Multi-signal voting classifier (torso angle, hip position, SAR, hip joint angle)
- Periodic beep-silence alert (2s ON / 5s OFF) with voice cancellation window
- Offline Vosk speech recognition for alert cancel
- GSM SIM800L module for SMS emergency alerts (3 contacts)
- No internet required — fully edge-deployed

# Tech Used:
# software:

# Hardware:
1.Raspberry Pi 4B (2GB+ RAM)

2.USB Webcam

3.USB Microphone

4.Piezoelectric Buzzer (GPIO pin 17)

5.SIM800L GSM Module (UART /dev/ttyS0)

# Circuit Diagram:


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

