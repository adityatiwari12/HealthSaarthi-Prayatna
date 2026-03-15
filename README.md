<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=HealthSaarthi&fontSize=80&fontColor=fff&animation=twinkling&fontAlignY=35&desc=हर%20पल,%20सही%20जाँच&descAlignY=60&descSize=28&descColor=rgba(255,255,255,0.8)"/>

<!-- Badges Row 1 -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Live%20Demo-brightgreen?style=for-the-badge&logo=statuspage&logoColor=white" />
  <img src="https://img.shields.io/badge/Hackathon-SIH%202025-orange?style=for-the-badge&logo=trophy&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-2.0.0-blue?style=for-the-badge&logo=semver&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge&logo=opensourceinitiative&logoColor=white" />
</p>

<!-- Badges Row 2 -->
<p align="center">
  <img src="https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Realtime-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/ESP32-IoT%20Core-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-CV%20Engine-00FFFF?style=for-the-badge&logo=python&logoColor=black" />
</p>

<br/>

<!-- Hero Statement -->
<h3>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=EF4444&center=true&vCenter=true&width=700&lines=India%27s+First+Intelligent+Emergency+Coordination+Platform;Real-Time+Hospital+Resource+Orchestration;IoT+Smart+Ambulance+%E2%80%94+%E2%82%B91%2C600+vs+%E2%82%B930+Lakhs;Zero+Phone+Calls.+Zero+Paperwork.+Zero+Delays." alt="Typing SVG" />
</h3>

<br/>

> **HealthSaarthi** connects patients, ambulances, and hospitals into one real-time intelligent ecosystem — eliminating the information silos that cost lives during medical emergencies across India.

<br/>

<!-- Quick Stats -->
<table align="center">
<tr>
<td align="center"><img src="https://img.shields.io/badge/-%E2%82%B91%2C600-red?style=flat-square&labelColor=black" /><br/><b>IoT Patch Cost</b><br/><sub>vs ₹30L Smart Ambulance</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-98%25-orange?style=flat-square&labelColor=black" /><br/><b>BLS Ambulances</b><br/><sub>in India — all upgradeable</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-12%20Min-green?style=flat-square&labelColor=black" /><br/><b>End-to-End</b><br/><sub>Patient → Prepared Hospital</sub></td>
<td align="center"><img src="https://img.shields.io/badge/-0-blue?style=flat-square&labelColor=black" /><br/><b>Phone Calls</b><br/><sub>in entire dispatch flow</sub></td>
</tr>
</table>

</div>

---

## 📋 Table of Contents

<div align="center">

| | Section | | Section |
|:---:|:---|:---:|:---|
| 🎯 | [The Problem](#-the-problem) | 🏗️ | [Architecture](#️-system-architecture) |
| 💡 | [The Solution](#-the-solution) | 🤖 | [Dispatch Algorithm](#-dispatch-algorithm) |
| ✨ | [Features](#-platform-features) | 🔧 | [IoT Hardware](#-iot-smart-ambulance) |
| 📱 | [Mobile Apps](#-mobile-applications) | 🚀 | [Getting Started](#-getting-started) |
| 🛠️ | [Tech Stack](#️-technology-stack) | 👥 | [Team](#-team) |

</div>

---

## 🚨 The Problem

<div align="center">
<img src="https://img.shields.io/badge/Every%204%20Minutes-Someone%20dies%20waiting%20for%20the%20right%20ambulance-red?style=for-the-badge" />
</div>

<br/>

```
🏥  Hospital A                    🏥  Hospital B                    🏥  Hospital C
━━━━━━━━━━━━━━                    ━━━━━━━━━━━━━━                    ━━━━━━━━━━━━━━
ICU: 4 free                       ICU: 0 free ❌                    ICU: 7 free
Ventilator: ✓                     Ventilator: ✗                     Ventilator: ✓
Cardiologist: ON DUTY             Cardiologist: OFF DUTY            Cardiologist: OFF DUTY

          🚑 Ambulance heading to Hospital B — NO ONE KNEW IT WAS FULL
```

> India's healthcare emergency response fails not because resources don't exist — but because they are **invisible to each other.** Ambulances drive blind. Hospitals prepare nothing. Patients pay with their lives.

**The three fatal gaps:**

- 🔴 **Information Silo** — Ambulance doesn't know which hospital has an ICU bed
- 🔴 **Identity Gap** — Doctor treats an unconscious patient with zero medical history  
- 🔴 **Coordination Void** — No city-level visibility over healthcare resources in real time

---

## 💡 The Solution

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                       │
│    STRANGER FINDS PATIENT  ──→  TAPS LOCK SCREEN  ──→  AI TRIGGERS  │
│           ↓                                               SOS + GPS   │
│    QR SCANNED BY DOCTOR    ←──  FULL HISTORY IN 3s                  │
│           ↓                                                           │
│    IoT PATCH APPLIED       ──→  LIVE VITALS STREAM  ──→  HOSPITAL   │
│           ↓                         TO HOSPITAL          PREPARES    │
│    AI DISPATCH ENGINE      ──→  OPTIMAL HOSPITAL   ──→  BED         │
│    scores all hospitals           SELECTED               RESERVED    │
│           ↓                                                           │
│    AMBULANCE ARRIVES       ──→  HOSPITAL READY     ──→  ZERO DELAY  │
│                                                                       │
│              Total time: Under 12 minutes. Zero phone calls.         │
└─────────────────────────────────────────────────────────────────────┘
```

</div>

---

## ✨ Platform Features

### 🚨 Smart Emergency Dispatch

<table>
<tr>
<td width="50%">

**AI-Powered Hospital Selection**
- Multi-variable scoring engine (not just nearest)
- Dynamic weights shift based on patient triage severity
- ICU availability + Specialist match + OSRM ETA + Stress Index
- Conflict resolution when two ambulances need same last bed
- Full reasoning shown to coordinator with confidence score

</td>
<td width="50%">

```json
{
  "selectedHospital": "Indore Central",
  "confidenceScore": 87,
  "etaMinutes": 6,
  "triageLevel": "CRITICAL",
  "reasons": [
    "✅ ICU available (4 free)",
    "✅ Cardiologist on duty",
    "✅ Blood type A+ in stock"
  ],
  "penalties": [
    "⚠️ Multiple incoming patients"
  ]
}
```

</td>
</tr>
</table>

---

### 🗺️ Resource Availability Map

> Real-time heatmap of hospital resources across the entire city

<div align="center">

| 🟢 Healthy | 🟡 Moderate Stress | 🔴 Critical |
|:---:|:---:|:---:|
| ICU > 60% free | ICU 30–60% free | ICU < 30% free |
| Specialists on duty | Some specialists available | No key specialists |
| Ventilators available | Limited ventilators | No ventilators |

</div>

Each hospital pin shows on hover:
```
┌─────────────────────────────────┐
│  🏥 Indore Central Hospital     │
│  📍 0.5 km away                 │
│                                  │
│  🛏  ICU:        ████░░  4/12   │
│  🫁  Ventilator: ██████  6/6    │
│  🫧  O₂:         █████░  8/10  │
│  🩸  Blood:      A+  O+  B-     │
│  👨‍⚕️  Cardio · Neuro · Ortho    │
│  🚑  ETA: 4 min                 │
│                                  │
│  [View Details]  [Book Ambulance]│
└─────────────────────────────────┘
```

---

### 🔬 IoT Smart Ambulance System

<div align="center">
<img src="https://img.shields.io/badge/Hardware%20Cost-₹1%2C600-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/Smart%20Ambulance%20Cost-₹30%2C00%2C000-darkred?style=for-the-badge" />
<img src="https://img.shields.io/badge/Cost%20Reduction-15%2C000x-brightgreen?style=for-the-badge" />
</div>

<br/>

> 98% of India's ambulances are Basic Life Support (BLS) — costing ₹8 lakhs. Smart ambulances cost ₹30–40 lakhs. We make every BLS ambulance smart for ₹1,600.

```
Patient Wrist/Chest
      │
      ▼
┌─────────────┐     MQTT/GSM      ┌──────────────────┐
│  IoT Patch  │ ───────────────→  │  Firebase RT DB  │
│             │                   └────────┬─────────┘
│  ESP32      │                            │
│  MAX30102   │                            ▼
│  MPU6050    │                   ┌──────────────────┐
│  SIM800L    │                   │ Hospital Dashboard│
│             │                   │ Live vitals feed  │
│  HR  SpO₂   │                   │ Triage scoring    │
│  BP  Temp   │                   │ Pre-arrival prep  │
└─────────────┘                   └──────────────────┘
```

**Bill of Materials:**

| Component | Function | Cost |
|:---|:---|---:|
| ESP32 Dev Board | Main MCU + WiFi | ₹350 |
| MAX30102 | Heart Rate + SpO₂ | ₹200 |
| MPU6050 | Accelerometer + Gyro | ₹100 |
| SIM800L | GSM Fallback Network | ₹450 |
| LiPo Battery + PCB | Power Supply | ₹300 |
| Casing + Misc | Enclosure | ₹200 |
| **Total** | | **₹1,600** |

---

### 📱 Always-On Emergency Lock Screen

<table>
<tr>
<td align="center" width="33%">

**🔒 Lock Screen State**
```
┌──────────────┐
│  11:42       │
│              │
│     👤       │
│   Aditya     │
│              │
│  TAP IN      │
│  EMERGENCY   │
│  (breathing  │
│   red pulse) │
└──────────────┘
```
*Visible without unlocking*

</td>
<td align="center" width="33%">

**🚨 Post-Tap State**
```
┌──────────────┐
│ 🔴 EMERGENCY │
│   ACTIVATED  │
│              │
│ [  QR CODE  ]│
│  Doctor Only │
│              │
│ Riya  📞    │
│ Arjun 📞    │
│              │
│ [CALL ALL]   │
└──────────────┘
```
*One tap triggers everything*

</td>
<td align="center" width="33%">

**📡 AI Agent Status**
```
┌──────────────┐
│ 📍 Location  │
│ captured ✓   │
│              │
│ 📲 Notifying │
│ Riya...      │
│ ✓ Notified   │
│              │
│ 📲 Notifying │
│ Arjun...     │
│ ✓ Notified   │
│              │
│ 🚑 Locating  │
│ ambulance... │
└──────────────┘
```
*Live AI agent feed*

</td>
</tr>
</table>

---

### 🏥 Hospital Command Center

> City-level emergency coordination dashboard for hospital coordinators

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  🔴 LIVE    HealthSaarthi Command Center — Indore         🕐 14:32:07       │
├──────────────────────────────────────────────────────────────────────────────┤
│ 🔴 Patient #1 — Amb A-04 — ETA 4min — SpO₂:91%↓ — CRITICAL — ICU Reserved │
│ 🟡 Patient #2 — Amb A-07 — ETA 11min — HR:88 — STABLE — Ward Reserved      │
├───────────────────────────────────┬──────────────────────────────────────────┤
│                                   │  City Resource Overview                  │
│                                   │  ┌──────────┐  ┌──────────┐             │
│         [ LEAFLET MAP ]           │  │🛏 23/89  │  │🫁 11 free│             │
│                                   │  │ ICU Beds │  │Ventilators│            │
│   🏥🟢  🏥🟡  🏥🔴               │  └──────────┘  └──────────┘             │
│                                   │  ┌──────────┐  ┌──────────┐             │
│   🚑→→  🚑→→→→                   │  │🚑 7/12   │  │👨‍⚕️ 14    │             │
│                                   │  │Ambulances│  │ER Doctors│             │
│                                   │  └──────────┘  └──────────┘             │
│                                   │                                          │
│                                   │  ⚠️ Indore Central → CRITICAL CAPACITY  │
│                                   ├──────────────────────────────────────────┤
│                                   │  Active Ambulances                       │
│                                   │  🚑 A-04 ● → Indore Central  4min [View]│
│                                   │  🚑 A-07 ● → City General   11min [View]│
│                                   │  🚑 A-02 ○  Available — MG Road         │
│                                   ├──────────────────────────────────────────┤
│                                   │  ⚡ DISPATCH OPTIMAL AMBULANCE           │
└───────────────────────────────────┴──────────────────────────────────────────┘
```

---

## 🤖 Dispatch Algorithm

The core intelligence of HealthSaarthi. A multi-variable weighted scoring engine that selects the optimal hospital — not just the nearest.

### Triage Score Formula

```python
def compute_triage_score(vitals, patient):
    score = 100
    
    # SpO2 — highest weight (most critical vital)
    if vitals.spo2 < 90:   score -= 35
    elif vitals.spo2 < 94: score -= 20
    elif vitals.spo2 < 97: score -= 8
    
    # Heart Rate deviation from normal
    if vitals.hr > 130:    score -= 25
    elif vitals.hr < 50:   score -= 25
    elif vitals.hr > 110:  score -= 15
    
    # Blood Pressure (systolic)
    if vitals.bp_sys > 180: score -= 20
    elif vitals.bp_sys < 80: score -= 25
    
    # Pre-existing conditions
    if 'cardiac' in patient.conditions:  score -= 10
    if patient.age > 70:                 score -= 8
    
    return max(0, min(100, score))
```

### Hospital Scoring Weights (Dynamic)

| Parameter | CRITICAL (<30) | SERIOUS (30–55) | MODERATE (55–75) |
|:---|:---:|:---:|:---:|
| ICU Availability | **30%** | 25% | 20% |
| Specialist Match | 20% | **25%** | **30%** |
| OSRM ETA | **30%** | 20% | 15% |
| Hospital Capacity | 10% | **20%** | **25%** |
| Ventilator | 10% | 10% | 10% |

### Conflict Resolution

```
Ambulance A (Triage: 28 — CRITICAL)  ─→  Last ICU bed at Hospital X
Ambulance B (Triage: 45 — SERIOUS)   ─→  Last ICU bed at Hospital X
                    ↓
Priority = (100 - triageScore) + (1/eta) × 10
                    ↓
Ambulance A WINS → ICU reserved
Ambulance B RE-ROUTED → Next best hospital auto-selected
```

---

## 🛠️ Technology Stack

<div align="center">

### Frontend
![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet.js-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_RT_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=eclipsemosquitto&logoColor=white)

### AI / ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=python&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### IoT Hardware
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878A?style=for-the-badge&logo=arduino&logoColor=white)
![Bluetooth](https://img.shields.io/badge/BLE_5.0-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)

### Maps & Routing
![OpenStreetMap](https://img.shields.io/badge/OpenStreetMap-7EBC6F?style=for-the-badge&logo=openstreetmap&logoColor=white)
![OSRM](https://img.shields.io/badge/OSRM_Routing-FF6B35?style=for-the-badge&logo=mapbox&logoColor=white)

</div>

---

## 🏗️ System Architecture

```
                              HealthSaarthi Platform
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                           │
│   📱 Patient App          👨‍⚕️ Doctor App         🚑 Driver App           │
│   ┌──────────┐            ┌──────────┐           ┌──────────┐           │
│   │Lock Screen│           │QR Scanner│           │Nav + ETA │           │
│   │SOS Trigger│           │Pt History│           │Vitals    │           │
│   │QR Display │           │Rx + Docs │           │Dashboard │           │
│   └────┬─────┘            └────┬─────┘           └────┬─────┘           │
│        │                       │                       │                  │
│        └───────────────────────┴───────────────────────┘                 │
│                                │                                          │
│                    ┌───────────▼──────────┐                              │
│                    │   Firebase RT DB      │                              │
│                    │   + Node/Express API  │                              │
│                    └───────────┬──────────┘                              │
│                                │                                          │
│        ┌───────────────────────┼───────────────────────┐                 │
│        │                       │                       │                  │
│   ┌────▼──────┐         ┌─────▼──────┐        ┌──────▼──────┐          │
│   │IoT Patch  │         │AI Dispatch │        │Command Center│          │
│   │ESP32+MQTT │         │Engine      │        │Web Dashboard │          │
│   │Live Vitals│         │Triage Score│        │Multi-Hospital│          │
│   │GSM Backup │         │OSRM Router │        │Resource Map  │          │
│   └───────────┘         └────────────┘        └─────────────┘           │
│                                                                           │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 📱 Mobile Applications

### Patient App
- 🔒 Always-on lock screen emergency widget
- 📲 One-tap AI agent SOS trigger
- 📍 Auto GPS location broadcast to family
- 🔐 Encrypted QR with full medical history
- 💓 IoT patch vitals viewer
- 🌐 Multilingual support (Hindi + regional languages)

### Doctor App
- 📷 QR scanner → instant patient history
- 🩺 Live vitals feed from IoT patch
- 💊 Prescription generation
- 📄 PDF report export
- 🎥 Telemedicine consultation

### Driver / Paramedic App
- 🗺️ OSRM turn-by-turn navigation
- 📊 Patient vitals glanceable card
- 🏥 Destination hospital details
- ⏱️ Live ETA countdown
- 🔄 Re-routing on condition change

---

## 🚀 Getting Started

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
python >= 3.9
```

### Installation

```bash
# Clone the repository
git clone https://github.com/your-org/healthsaarthi.git
cd healthsaarthi

# Install frontend dependencies
cd client && npm install

# Install backend dependencies
cd ../server && npm install

# Install ML dependencies
cd ../ml && pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Add your Firebase config, MQTT broker URL
```

### Environment Variables

```env
# Firebase
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_DATABASE_URL=your_db_url

# MQTT (HiveMQ Free Tier)
MQTT_BROKER_URL=your_hivemq_url
MQTT_TOPIC_VITALS=healthsaarthi/vitals

# Maps
VITE_OSRM_BASE_URL=http://router.project-osrm.org
```

### Run Development

```bash
# Terminal 1 — Frontend
cd client && npm run dev

# Terminal 2 — Backend
cd server && npm run dev

# Terminal 3 — IoT Simulator (if no hardware)
cd iot && python simulate_vitals.py
```

### IoT Hardware Setup

```cpp
// Flash ESP32 with PlatformIO
// platformio.ini already configured

// 1. Wire MAX30102 → ESP32 (I2C: SDA=21, SCL=22)
// 2. Wire SIM800L → ESP32 (TX=17, RX=16)
// 3. Flash firmware
cd iot/firmware && pio run --target upload

// Device auto-connects to MQTT and begins streaming
```

---

## 📁 Project Structure

```
healthsaarthi/
├── 📱 client/                    # React + TypeScript Frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── CommandCenter/    # Hospital coordination dashboard
│   │   │   ├── ResourceMap/      # Leaflet resource heatmap
│   │   │   ├── TickerStrip/      # Live emergency feed
│   │   │   ├── AmbulanceList/    # Active ambulance tracker
│   │   │   └── DispatchPanel/    # AI dispatch with reasoning
│   │   ├── stores/
│   │   │   └── useCommandStore.ts # Zustand state management
│   │   └── hooks/
│   │       ├── useIoTVitals.ts   # MQTT vitals subscription
│   │       └── useDispatch.ts    # Dispatch algorithm hook
│
├── 🖥️  server/                   # Node.js + Express Backend
│   ├── routes/
│   │   ├── dispatch.js           # Hospital scoring API
│   │   ├── hospitals.js          # Resource management
│   │   └── patients.js           # Patient profile + QR
│   └── services/
│       ├── osrm.js               # Route optimization
│       ├── mqtt.js               # IoT data broker
│       └── triage.js             # Scoring engine
│
├── 🤖 ml/                        # Python ML Services
│   ├── disease_detection/        # CNN ensemble (skin/oral/xray)
│   ├── pose_estimation/          # YOLOv8 exercise guidance
│   └── triage_model/             # Vitals-based triage scoring
│
├── 📡 iot/                       # ESP32 Firmware
│   ├── firmware/                 # PlatformIO project
│   │   ├── src/main.cpp          # Main firmware loop
│   │   ├── sensors/              # MAX30102 + MPU6050 drivers
│   │   └── network/              # MQTT + GSM fallback
│   └── simulate_vitals.py        # Software simulator
│
└── 📱 mobile/                    # React Native Apps
    ├── patient-app/              # Lock screen + SOS
    └── doctor-app/               # QR scanner + history
```

---

## 🎯 Problem Statement Alignment

> **PS:** *"Intelligent, real-time healthcare resource sharing and coordination platform that enables dynamic visibility, allocation, and optimization of medical resources across multiple hospitals"*

| PS Requirement | HealthSaarthi Solution | Status |
|:---|:---|:---:|
| Real-time resource visibility | Live resource map with 4s refresh | ✅ |
| Multi-hospital coordination | Cross-hospital scoring + conflict resolution | ✅ |
| Dynamic resource allocation | Auto bed reservation + release on admission | ✅ |
| Intelligent patient transfer | AI dispatch with full reasoning engine | ✅ |
| Emergency delay reduction | Pre-arrival preparation via IoT vitals | ✅ |
| System efficiency | Zero manual handoffs in entire flow | ✅ |
| Ambulance coordination | Live fleet tracking + OSRM optimization | ✅ |
| Infrastructure visibility | Hospital stress index + city coordinator view | ✅ |

---

## 🌟 What Makes HealthSaarthi Different

<table>
<tr>
<th>Feature</th>
<th>Others</th>
<th>HealthSaarthi</th>
</tr>
<tr>
<td>Ambulance Intelligence</td>
<td>GPS tracking only</td>
<td>Live patient vitals + AI pre-routing</td>
</tr>
<tr>
<td>Hospital Selection</td>
<td>Nearest hospital</td>
<td>Multi-variable scoring with reasoning</td>
</tr>
<tr>
<td>Patient Identity</td>
<td>Manual intake form on arrival</td>
<td>QR scan → full history in 3 seconds</td>
</tr>
<tr>
<td>Resource Data</td>
<td>Manual staff updates (hours of lag)</td>
<td>Auto-updates via IoT geofence triggers</td>
</tr>
<tr>
<td>Smart Ambulance Cost</td>
<td>₹30–40 Lakhs</td>
<td>₹1,600 IoT patch on any BLS ambulance</td>
</tr>
<tr>
<td>Unknown Patient</td>
<td>No solution</td>
<td>Always-on lock screen + bystander SOS</td>
</tr>
<tr>
<td>Conflict Resolution</td>
<td>First-come-first-served</td>
<td>Triage-score-based priority engine</td>
</tr>
</table>

---

## 👥 Team

<div align="center">

| | Member | Role |
|:---:|:---|:---|
| 👨‍💻 | **Aditya** | Frontend Lead + OpenCV Specialist |
| 👨‍💻 | Team Member 2 | Backend + IoT Integration |
| 👨‍💻 | Team Member 3 | ML + AI Models |
| 👨‍💻 | Team Member 4 | Mobile Apps |

**Institution:** B.Tech — Computer Science Engineering

</div>

---

## 📄 License

```
MIT License — HealthSaarthi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, merge, publish, distribute, sublicense
— subject to the condition that healthcare outcomes always come first.
```

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&text=हर%20पल,%20सही%20जाँच&fontSize=30&fontColor=fff&animation=twinkling&fontAlignY=65"/>

**HealthSaarthi** — Built with ❤️ for India's 1.4 Billion

*The right care. The right place. The right time.*

<br/>

[![GitHub stars](https://img.shields.io/github/stars/your-org/healthsaarthi?style=social)](https://github.com/your-org/healthsaarthi)
[![GitHub forks](https://img.shields.io/github/forks/your-org/healthsaarthi?style=social)](https://github.com/your-org/healthsaarthi)
[![GitHub watchers](https://img.shields.io/github/watchers/your-org/healthsaarthi?style=social)](https://github.com/your-org/healthsaarthi)

</div>
