# 💊 DoseGuardian – Intelligent Pill-Taking Assistant
DoseGuardian is an embedded-system–based intelligent medication reminder and monitoring solution designed to help patients take their prescribed medicines on time, especially elderly patients and individuals under long-term treatment.
## 📌 Aim
To design and implement a smart medication reminder system that alerts users at scheduled medicine times and monitors whether the medicine was taken or missed.
## 🎯 Objectives
- Display real-time date and time using RTC on an LCD
- Allow users to modify RTC settings via a 4×4 keypad
- Enable setting and editing of medicine schedules
- Generate alerts when the current time matches the medicine schedule
- Indicate missed doses using visual alerts (LED)
## 🧩 System Overview
### Main Components
- LPC2148 Microcontroller
- RTC (Real-Time Clock)
- 16×2 LCD Display
- 4×4 Matrix Keypad
- Buzzer
- Switches
- LED
- USB-UART Converter / DB-9 Cable
## ⚙️ Hardware Requirements
- LPC2148
- 16×2 LCD
- 4×4 Matrix Keypad
- Buzzer
- Push Buttons (Switch1, Switch2)
- LED
- USB-UART Converter / DB-9 Cable
## 💻 Software Requirements
- Embedded C
- Flash Magic
## 🔁 Working Principle
### Setting Medicine Schedule
User presses Switch1, enters medicine time via keypad, the schedule is stored in microcontroller memory, and the LCD displays RTC info with saved medicine times.
### Real-Time Monitoring
The microcontroller continuously checks RTC time and compares it with stored schedules.
### Alert Mechanism
The LCD displays “Take Medicine Now” and the buzzer turns ON/OFF at fixed intervals.
### User Acknowledgment
The user presses Switch2 to confirm intake; if not pressed within the given time, the red LED turns ON indicating a missed dose.
## 🧠 Software Flow
Initialize RTC, LCD, Keypad, and Buzzer, display current date and time on LCD, accept medicine schedule input when Switch1 is pressed, continuously monitor RTC, trigger alert when time matches medicine schedule, wait for acknowledgment via Switch2, resume monitoring, and turn ON red LED if the dose is missed.
## Output on hardware as well as proteus  
![WhatsApp Image 2025-12-29 at 21 11 31](https://github.com/user-attachments/assets/926775a5-820d-4a6a-88f4-3bf0203494b3)  
---
![WhatsApp Image 2025-12-29 at 21 11 32](https://github.com/user-attachments/assets/8f3a6f22-a23f-4b51-8677-8ec4bc4b22fc)  
---
![WhatsApp Image 2025-12-29 at 21 11 31 (1)](https://github.com/user-attachments/assets/712f5a80-1a5e-4bf2-88a0-885e6e2f5bb5)  
---
<img width="1920" height="1020" alt="Screenshot 2025-12-29 153310" src="https://github.com/user-attachments/assets/a758750d-6e54-43f9-b17b-aed73b8b7db7" />  
---
<img width="1920" height="1080" alt="Screenshot 2025-12-29 154225" src="https://github.com/user-attachments/assets/0e289acf-1989-4255-a485-fd1d1d322ba6" />  
---





## 🔄 Optional Enhancements
- Scroll-based menu navigation using Up/Down keys
- Cursor-based RTC editing using Left/Right arrows
- Multiple medicine schedules
- GSM/SMS alert integration
- IoT and mobile app support
## 🚀 Applications
- Elderly care systems
- Home healthcare
- Hospitals and clinics
- Personal medication management
## 📈 Future Scope
- Mobile app integration
- Cloud-based monitoring
- Voice alerts
- Battery backup
## 👨‍💻 Author
**Kiran Murram**

