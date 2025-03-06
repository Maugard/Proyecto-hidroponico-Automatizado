Cultivando Futuro: Hydroponic System Project
Last updated: March 2025

🌱 Project Overview

Cultivando Futuro is an automated hydroponic farming home system designed to address food insecurity in El Salvador through scalable, water-efficient urban agriculture. The project features three versions (Económica, Media, Premium) tailored to households, entrepreneurs, and businesses, with IoT integration, solar power, and modular designs.

Key Metrics:

Target: Reduce water usage by 90% vs. traditional farming
ROI: 55.1% (Económica) to 82.3% (Premium) over 5 years
Market: 250K–300K urban households, 15K–20K small farmers

🚀 Project Phases
Phase 1: Market Validation & Prototyping (Months 1–6).

Objectives:

Validate demand in vulnerable communities (47.1% food insecurity rate).
Build MVP prototypes for all three versions.

Deliverables:
    a) Test 50 Económica units in San Salvador households.
    b)Partner with 5 schools for institutional pilots.
    c)Finalize IoT architecture (ESP32 microcontrollers, MQTT protocol).

Phase 2: Production Scaling (Months 7–18).

Objectives:
    a) Ramp up manufacturing to 800 units/year.
    b) Secure partnerships with MAG (Ministry of Agriculture) and local NGOs.

Key Actions:

Version	    Units (Year 1)	Price	Key Features
Económica	500	            $286	Manual irrigation, steel frame
Media	    250	            $626	pH/EC sensors, 50W solar panel
Premium	    50	            $1,185	Auto-dosing, 100W solar, IoT app

Milestones:
    a) Train 100 users via workshops.
    b) Achieve 85% water savings in pilot sites.

Phase 3: Expansion & Automation (Years 2–5).

Objectives:
    a)Deploy 2,275 units by Year 5.
    b)Integrate predictive maintenance AI.

Roadmap:
Year 2: Launch mobile app for Premium users (real-time pH/EC monitoring).
Year 3: Partner with 200+ restaurants for Premium systems.
Year 5: Achieve 55–82.3% ROI across versions.

💻 Technical Setup
Hardware Requirements:

Microcontrollers: Arduino Mega (Económica/Media), ESP32 (Premium)
Sensors: pH (5.5–6.5 range), EC (1.2–2.5 mS/cm), DHT22 (humidity/temp)
Power: 50W–100W solar panels + 12V batteries

Software Stack:

IoT Platform: AWS IoT Core
Database: InfluxDB (time-series data)
Frontend: React.js dashboard + Firebase for alerts
python

# Example sensor calibration script (pH/EC)
def calibrate_ph(voltage_reading):
    slope = 3.5  # From factory calibration
    offset = 0.2
    return (voltage_reading * slope) + offset

🤝 How to Contribute

Hardware: Improve modular PVC frame designs (CAD files).
Software: Develop open-source firmware for ESP32 (GitHub repo).

Community: Join training workshops in San Salvador (Pending).

📄 License
GNU GPLv3 — Open-source for non-commercial use in El Salvador. Commercial licensing available.

❓ FAQs
Q: How much space does the system require?
A: 1.5 x 2.5m² for each of the three models.

Q: What crops are supported?
A: Cherry tomatoes, lettuce, arugula, basil (4–5 plants/m²).

For project documentation, financial models, or partnership inquiries, email maugard@gmail.com 🌟
