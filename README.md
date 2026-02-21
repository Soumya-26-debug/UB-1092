# UB-1092
# CleanValue – AI & IoT based rewrad driven  Waste Management System

 CleanValue is a smart waste management prototype that uses AI, IoT, and a reward-based mechanism to encourage proper waste segregation in urban areas.

---

## Problem Statement

Indian cities generate over 62 million tonnes of municipal solid waste annually, yet less than 30% is properly segregated. The lack of citizen incentives leads to mixed waste, increased landfill burden, environmental pollution, and higher municipal processing costs.

Traditional waste systems focus only on collection rather than encouraging responsible disposal behavior at the individual level. There is a need for an intelligent, incentive-driven system that promotes proper segregation while remaining financially sustainable.

---

## Proposed Solution

CleanValue is an AI and IoT-enabled smart dustbin system that:

- Authenticates users using a QR code
- Detects waste type using OpenCV and a trained ML model
- Measures waste weight using a load sensor
- Sends data (user_id, waste_type, weight) to a Django backend
- Calculates reward points based on weight and category
- Updates user accounts in real time
- Displays advertisements on the smart bin screen to generate revenue

This creates a self-sustaining, behavior-driven waste ecosystem.

---

##  Tech Stack

### Frontend
- React 

### Backend
- Django (Python)
- REST APIs
- SQLite / PostgreSQL (Database)

### AI & Computer Vision
- OpenCV
- Python
- ML Waste Classification Model

### Hardware (Prototype Level)
- Webcam (for QR & waste detection)
- Load Cell (Weight Measurement)
- Microcontroller (Future Integration)

---

## Project Structure
smart_bin/
│
├── main.py
├── qr_module.py
├── waste_detector.py
├── weight_sensor.py
├── api_client.py
└── config.py

Flow:
- Scan QR Code
- Detect waste type
- Measure weight
- Send data to backend
- Receive reward response

---

## Future Enhancements

- Real ML model integration
- Fraud detection system
- Carbon footprint tracking
- Smart City dashboard
- Cloud deployment

---

##  Impact

CleanValue promotes sustainable urban waste management by combining technology, incentives, and smart governance, creating cleaner and smarter cities.

---

##  Developed For

Hackathon / Smart City Innovation Challenge
