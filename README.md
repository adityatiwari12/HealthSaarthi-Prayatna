<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=HealthSaarthi&fontSize=90&fontColor=fff&animation=twinkling&fontAlignY=38&desc=हर%20पल,%20सही%20जाँच%20%E2%80%94%20The%20Right%20Care.%20The%20Right%20Place.%20The%20Right%20Time.&descAlignY=62&descSize=20&descColor=rgba(255,255,255,0.85)"/>



<p align="center">
  <img src="https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Realtime-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/ESP32-IoT%20Core-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/OSRM-Route%20Engine-FF6B35?style=for-the-badge&logo=openstreetmap&logoColor=white" />
</p>

<br/>

<h3>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&pause=1000&color=EF4444&center=true&vCenter=true&width=750&lines=India's+First+Intelligent+Emergency+Coordination+Platform;Real-Time+Multi-Hospital+Resource+Orchestration;IoT+Smart+Ambulance+%E2%80%94+%E2%82%B91%2C600+vs+%E2%82%B930+Lakhs;Zero+Phone+Calls.+Zero+Paperwork.+Zero+Delays." alt="Typing SVG" />
</h3>

<br/>

> **HealthSaarthi** is an intelligent, real-time healthcare coordination platform that connects patients, ambulances, and hospitals into one unified ecosystem — eliminating the information silos that cost lives during medical emergencies across India.

<br/>

<table align="center">
<tr>
<td align="center">
  <img src="https://img.shields.io/badge/-%E2%82%B91%2C600-EF4444?style=flat-square&labelColor=1a1a2e" /><br/>
  <b>IoT Patch Cost</b><br/>
  <sub>vs ₹30–40L Smart Ambulance</sub>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/-98%25-F97316?style=flat-square&labelColor=1a1a2e" /><br/>
  <b>BLS Ambulances</b><br/>
  <sub>in India — all upgradeable</sub>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/-12%20Min-22C55E?style=flat-square&labelColor=1a1a2e" /><br/>
  <b>End-to-End Response</b><br/>
  <sub>Patient found → Hospital ready</sub>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/-0-3B82F6?style=flat-square&labelColor=1a1a2e" /><br/>
  <b>Phone Calls</b><br/>
  <sub>in entire dispatch flow</sub>
</td>
<td align="center">
  <img src="https://img.shields.io/badge/-15%2C000x-A855F7?style=flat-square&labelColor=1a1a2e" /><br/>
  <b>Cost Reduction</b><br/>
  <sub>vs conventional smart ambulance</sub>
</td>
</tr>
</table>

</div>

---

## 📋 Table of Contents

<div align="center">

| | Section | | Section |
|:---:|:---|:---:|:---|
| 🚨 | [The Problem](#-the-problem) | 🤖 | [Dispatch Algorithm](#-dispatch-algorithm) |
| 💡 | [The Solution](#-the-solution) | 🔬 | [IoT Hardware](#-iot-smart-ambulance-system) |
| ✨ | [Platform Features](#-platform-features) | 🏗️ | [System Architecture](#️-system-architecture) |
| 📱 | [Mobile Apps](#-mobile-applications) | 🎯 | [PS Alignment](#-problem-statement-alignment) |
| 🛠️ | [Tech Stack](#️-technology-stack) | 🌟 | [Differentiation](#-what-makes-healthsaarthi-different) |

</div>

---

## 🚨 The Problem

<div align="center">
<img src="https://img.shields.io/badge/Every%204%20Minutes-Someone%20dies%20waiting%20for%20the%20right%20ambulance-red?style=for-the-badge" />
</div>

<br/>

```
🏥  Hospital A                    🏥  Hospital B                    🏥  Hospital C
━━━━━━━━━━━━━━━━                  ━━━━━━━━━━━━━━━━                  ━━━━━━━━━━━━━━━━
ICU: 4 free ✓                     ICU: 0 free ❌                    ICU: 7 free ✓
Ventilator: ✓                     Ventilator: ✗                     Ventilator: ✓
Cardiologist: ON DUTY             Cardiologist: OFF DUTY            Cardiologist: OFF DUTY

                  🚑 Ambulance heading to Hospital B — NO ONE KNEW IT WAS FULL
```

> India's emergency healthcare fails not because resources don't exist — but because they are **invisible to each other.** Ambulances drive blind. Hospitals prepare nothing. Patients pay with their lives.

<br/>

**The three fatal gaps no existing solution addresses together:**

| Gap | Reality Today |
|:---|:---|
| 🔴 **Information Silo** | Ambulance has no visibility into which hospital has an ICU bed, ventilator, or the right specialist on duty |
| 🔴 **Identity Gap** | An unconscious patient arrives with zero medical history — no blood type, no allergies, no conditions |
| 🔴 **Coordination Void** | No city-level, real-time view of healthcare resources across hospitals exists for emergency coordinators |

---

## 💡 The Solution

<div align="center">

```
╔═════════════════════════════════════════════════════════════════════════╗
║                                                                         ║
║   STRANGER FINDS PATIENT  ──▶  TAPS LOCK SCREEN  ──▶  AI TRIGGERS     ║
║          │                                              SOS + GPS       ║
║          ▼                                                              ║
║   QR SCANNED BY DOCTOR    ◀──  FULL HISTORY IN 3s ◀── DOCTOR APP      ║
║          │                                                              ║
║          ▼                                                              ║
║   IoT PATCH APPLIED       ──▶  LIVE VITALS STREAM ──▶  HOSPITAL       ║
║          │                      TO HOSPITAL              PREPARES      ║
║          ▼                                                              ║
║   AI DISPATCH ENGINE      ──▶  OPTIMAL HOSPITAL   ──▶  BED            ║
║   scores all hospitals          SELECTED                RESERVED       ║
║          │                                                              ║
║          ▼                                                              ║
║   AMBULANCE ARRIVES       ──▶  HOSPITAL READY     ──▶  ZERO DELAY     ║
║                                                                         ║
║         Total time: Under 12 minutes. Zero phone calls. Zero forms.    ║
╚═════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## ✨ Platform Features

### 🚨 Smart Emergency Dispatch

<table>
<tr>
<td width="50%">

**AI-Powered Hospital Selection**
- Multi-variable scoring engine — not just nearest hospital
- Dynamic weights shift based on live patient triage severity
- Scores: ICU availability + Specialist match + OSRM ETA + Stress Index
- Conflict resolution when two ambulances compete for the same last bed
- Full reasoning shown to coordinator with confidence score and alternatives

</td>
<td width="50%">

```json
{
  "selectedHospital": "Indore Central Hospital",
  "confidenceScore": 87,
  "triageLevel": "CRITICAL",
  "etaMinutes": 6,
  "reasons": [
    "✅ ICU available (4 free)",
    "✅ Cardiologist on duty",
    "✅ Blood type A+ in stock",
    "✅ Closest ETA (6 min)"
  ],
  "penalties": [
    "⚠️ 2 incoming ambulances"
  ],
  "alternatives": [
    { "hospital": "City General", "score": 71 },
    { "hospital": "MG Hospital",  "score": 58 }
  ]
}
```

</td>
</tr>
</table>

---

### 🗺️ Resource Availability Map

> Real-time city-wide heatmap of hospital resources — ICU beds, ventilators, O₂ cylinders, blood bank, and specialists — visible to coordinators at a glance.

<div align="center">

| 🟢 Healthy | 🟡 Moderate Stress | 🔴 Critical |
|:---:|:---:|:---:|
| ICU > 60% free | ICU 30–60% free | ICU < 30% free |
| All key specialists on duty | Some specialists available | No key specialists |
| Ventilators available | Limited ventilators | No ventilators |

</div>

Each hospital pin shows on hover:

```
┌──────────────────────────────────────┐
│  🏥 Indore Central Hospital          │
│  📍 0.5 km  ·  🟢 Healthy Capacity  │
│                                       │
│  🛏  ICU Beds:    ████░░░  4 / 12   │
│  🫁  Ventilators: ██████░  6 / 8    │
│  🫧  O₂ Supply:   █████░░  8 / 10   │
│  🩸  Blood Bank:  A+  O+  B-  AB+   │
│  👨‍⚕️  On Duty:   Cardio · Neuro · Ortho │
│  🚑  Nearest ETA: 4 min              │
│                                       │
│  [ View Details ]  [ Book Ambulance ]│
└──────────────────────────────────────┘
```

---

### 🔬 IoT Smart Ambulance System

<div align="center">

| | Basic BLS Ambulance | Conventional Smart Ambulance | **HealthSaarthi IoT Patch** |
|:---:|:---:|:---:|:---:|
| **Cost** | ₹8 Lakhs | ₹30–40 Lakhs | **₹1,600** |
| **Vitals Streaming** | ❌ | ✅ | ✅ |
| **Live Hospital Feed** | ❌ | ✅ | ✅ |
| **Retrofit Required** | — | Full vehicle replacement | **Patch on patient wrist** |

</div>

<br/>

> 98% of India's ambulances are Basic Life Support. We don't replace them. We make every one intelligent.

```
Patient Wrist / Chest
        │
        ▼
┌───────────────┐      MQTT over GSM/WiFi      ┌──────────────────────┐
│   IoT Patch   │ ─────────────────────────▶   │   Firebase RT DB     │
│               │                              └──────────┬───────────┘
│  ESP32        │                                         │
│  MAX30102     │                                         ▼
│  MPU6050      │                              ┌──────────────────────┐
│  SIM800L      │                              │  Hospital Dashboard  │
│               │                              │  · Live vitals feed  │
│  HR  ·  SpO₂  │                              │  · Triage scoring    │
│  BP  ·  Temp  │                              │  · Pre-arrival prep  │
└───────────────┘                              │  · Auto bed reserve  │
                                               └──────────────────────┘
```

**Bill of Materials — ₹1,600 total:**

| Component | Function | Cost |
|:---|:---|---:|
| ESP32 Dev Board | Main MCU + WiFi | ₹350 |
| MAX30102 | Heart Rate + SpO₂ | ₹200 |
| MPU6050 | Accelerometer + Motion | ₹100 |
| SIM800L | GSM Fallback (2G minimum) | ₹450 |
| LiPo Battery + PCB | Power Supply | ₹300 |
| Casing + Misc | Enclosure | ₹200 |
| **Total** | | **₹1,600** |

**That is a 15,000x cost reduction against a conventional smart ambulance.**

---

### 📱 Always-On Emergency Lock Screen

<table>
<tr>
<td align="center" width="33%">

**🔒 Lock Screen — Always Visible**
```
┌────────────────┐
│   11:42        │
│   Sun, Mar 15  │
│                │
│      👤        │
│    Aditya      │
│                │
│   ✚  TAP IN   │
│   EMERGENCY    │
│  (soft pulse)  │
│                │
│ ────────────── │
└────────────────┘
```
*No unlock required*

</td>
<td align="center" width="33%">

**🚨 Post-Tap — Instant Actions**
```
┌────────────────┐
│ 🔴 EMERGENCY   │
│   ACTIVATED    │
│                │
│ ┌────────────┐ │
│ │  QR CODE   │ │
│ │ ░░░░░░░░░░ │ │
│ │ Doctor Only│ │
│ └────────────┘ │
│                │
│ Riya    📞    │
│ Arjun   📞    │
│                │
│ [ CALL ALL ]   │
└────────────────┘
```
*One tap. Everything triggers.*

</td>
<td align="center" width="33%">

**📡 AI Agent Live Feed**
```
┌────────────────┐
│ 📍 Location    │
│    captured ✓  │
│                │
│ 📲 Notifying   │
│    Riya...     │
│ ✓  Notified    │
│                │
│ 📲 Notifying   │
│    Arjun...    │
│ ✓  Notified    │
│                │
│ 🚑 Locating    │
│    ambulance...│
└────────────────┘
```
*Live status, no guessing*

</td>
</tr>
</table>

---

### 🏥 Hospital Command Center

> City-level emergency coordination dashboard for hospital coordinators and emergency managers.

```
┌──────────────────────────────────────────────────────────────────────────────┐
│  🔴 LIVE    HealthSaarthi Command Center — Indore            🕐 14:32:07     │
├──────────────────────────────────────────────────────────────────────────────┤
│ 🔴 Patient #1 · Amb A-04 · ETA 4min · SpO₂: 91%↓ · CRITICAL · ICU Reserved │
│ 🟡 Patient #2 · Amb A-07 · ETA 11min · HR: 88bpm · STABLE   · Ward Reserved │
├─────────────────────────────────────┬────────────────────────────────────────┤
│                                     │  City Resource Overview — Live         │
│                                     │  ┌───────────┐   ┌───────────┐        │
│         [ LEAFLET MAP ]             │  │ 🛏 23/89  │   │ 🫁 11 free│        │
│                                     │  │ ICU Beds  │   │ Ventilators│       │
│   🏥🟢   🏥🟡   🏥🔴              │  └───────────┘   └───────────┘        │
│                                     │  ┌───────────┐   ┌───────────┐        │
│   🚑━━▶    🚑━━━━━▶                │  │ 🚑  7/12  │   │ 👨‍⚕️  14   │        │
│                                     │  │ Ambulances│   │ER Doctors │        │
│                                     │  └───────────┘   └───────────┘        │
│                                     │  ⚠️  Indore Central → CRITICAL         │
│                                     ├────────────────────────────────────────┤
│                                     │  Active Ambulances                     │
│                                     │  🚑 A-04 ● En Route · Central  4m [▶] │
│                                     │  🚑 A-07 ● En Route · General 11m [▶] │
│                                     │  🚑 A-02 ○ Available · MG Road         │
│                                     ├────────────────────────────────────────┤
│                                     │  ⚡ DISPATCH OPTIMAL AMBULANCE          │
└─────────────────────────────────────┴────────────────────────────────────────┘
```

---

## 🤖 Dispatch Algorithm

The intelligence core of HealthSaarthi. A multi-variable weighted scoring engine that selects the optimal hospital — not the nearest one.

### Step 1 — Triage Score (computed from live IoT vitals)

```python
def compute_triage_score(vitals, patient):
    score = 100

    # SpO₂ — highest weight (most critical indicator)
    if vitals.spo2 < 90:    score -= 35
    elif vitals.spo2 < 94:  score -= 20
    elif vitals.spo2 < 97:  score -= 8

    # Heart Rate deviation from normal (60–100 bpm)
    if vitals.hr > 130:     score -= 25
    elif vitals.hr < 50:    score -= 25
    elif vitals.hr > 110:   score -= 15
    elif vitals.hr < 60:    score -= 10

    # Blood Pressure — systolic
    if vitals.bp_sys > 180: score -= 20
    elif vitals.bp_sys < 80: score -= 25

    # Pre-existing conditions (from QR health record)
    if 'cardiac' in patient.conditions:      score -= 10
    if 'hypertension' in patient.conditions: score -= 5
    if patient.age > 70:                     score -= 8

    return max(0, min(100, score))

# CRITICAL < 30  |  SERIOUS 30–55  |  MODERATE 55–75  |  STABLE > 75
```

### Step 2 — Dynamic Hospital Scoring Weights

| Parameter | 🔴 CRITICAL (<30) | 🟡 SERIOUS (30–55) | 🟢 MODERATE (55–75) |
|:---|:---:|:---:|:---:|
| ICU Availability | **30%** | 25% | 20% |
| Specialist Match | 20% | **25%** | **30%** |
| OSRM ETA | **30%** | 20% | 15% |
| Hospital Capacity | 10% | **20%** | **25%** |
| Ventilator | 10% | 10% | 10% |

> When the patient is CRITICAL, ETA weight doubles. When stable, specialist precision matters more than speed. Weights shift automatically.

### Step 3 — Conflict Resolution

```
Ambulance A  (Triage Score: 28 — CRITICAL)  ──▶  Last ICU bed at Hospital X
Ambulance B  (Triage Score: 45 — SERIOUS)   ──▶  Last ICU bed at Hospital X
                              │
                              ▼
       Priority = (100 − triageScore) + (1 / etaMinutes) × 10
                              │
                              ▼
    Ambulance A WINS  →  ICU reserved, hospital notified
    Ambulance B REROUTED  →  Next best hospital auto-selected via re-score
```

No first-come-first-served. Sicker patient always wins.

---

## 🏗️ System Architecture

```
                              HealthSaarthi Platform
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                           │
│   📱 Patient App         👨‍⚕️ Doctor App          🚑 Driver App           │
│   ┌────────────┐         ┌────────────┐          ┌────────────┐         │
│   │ Lock Screen│         │ QR Scanner │          │ Navigation │         │
│   │ SOS Trigger│         │ Pt History │          │ Vitals Card│         │
│   │ QR Display │         │ Rx + Docs  │          │ ETA Display│         │
│   └─────┬──────┘         └─────┬──────┘          └─────┬──────┘         │
│         │                      │                        │                 │
│         └──────────────────────┴────────────────────────┘                │
│                                │                                          │
│                   ┌────────────▼─────────────┐                           │
│                   │   Firebase Realtime DB    │                           │
│                   │   + Node.js / Express API │                           │
│                   └────────────┬─────────────┘                           │
│                                │                                          │
│         ┌──────────────────────┼──────────────────────┐                  │
│         │                      │                       │                  │
│   ┌─────▼──────┐        ┌──────▼──────┐       ┌───────▼──────┐          │
│   │ IoT Patch  │        │ AI Dispatch │       │Command Center│           │
│   │ ESP32+MQTT │        │ Engine      │       │ Web Dashboard│           │
│   │ Live Vitals│        │ Triage Score│       │ Multi-Hospital│          │
│   │ GSM Backup │        │ OSRM Router │       │ Resource Map  │          │
│   └────────────┘        └─────────────┘       └──────────────┘           │
│                                                                           │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 📱 Mobile Applications

### Patient App
- 🔒 Always-on lock screen emergency widget — visible without unlocking
- 📲 One-tap AI agent SOS — alerts all family members with GPS location instantly
- 🔐 Encrypted time-limited QR with full medical history — doctor access only
- 💓 IoT patch vitals viewer — see your own live health data
- 🌐 Multilingual support — Hindi and regional Indian languages

### Doctor App
- 📷 QR scanner → instant patient history, allergies, medications, reports
- 🩺 Live vitals feed from IoT patch during consultation
- 💊 Prescription generation with Jan Aushadhi integration
- 📄 PDF medical report export
- 🎥 Telemedicine consultation for remote triage

### Driver / Paramedic App
- 🗺️ OSRM turn-by-turn navigation to AI-selected hospital
- 📊 Glanceable patient vitals card — HR, SpO₂, BP at a glance
- 🏥 Destination hospital details — bed reserved, specialist alerted
- ⏱️ Live ETA countdown
- 🔄 Auto re-routing if patient condition deteriorates mid-transit

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

## 🎯 Problem Statement Alignment

> **PS 25108:** *"Intelligent, real-time healthcare resource sharing and coordination platform that enables dynamic visibility, allocation, and optimization of medical resources across multiple hospitals to reduce emergency delays and improve system efficiency."*

| PS Requirement | HealthSaarthi Solution | Status |
|:---|:---|:---:|
| Real-time resource visibility | Live resource map with 4s auto-refresh across all hospitals | ✅ |
| Multi-hospital coordination | Cross-hospital scoring engine with city-wide coordinator view | ✅ |
| Dynamic resource allocation | Auto bed reservation + auto-release on admission via geofence | ✅ |
| Intelligent patient transfer | AI dispatch with triage-based multi-variable scoring + reasoning | ✅ |
| Emergency delay reduction | Pre-arrival hospital preparation via live IoT vitals stream | ✅ |
| System efficiency | Zero manual handoffs across entire patient journey | ✅ |
| Ambulance coordination | Live fleet tracking + OSRM route optimization | ✅ |
| Infrastructure visibility | Hospital stress index + city coordinator dashboard | ✅ |
| Conflict resolution | Triage-priority bed arbitration when resources are contested | ✅ |

---

## 🌟 What Makes HealthSaarthi Different

<table>
<tr>
<th width="25%">Capability</th>
<th width="35%">Existing Solutions</th>
<th width="40%">HealthSaarthi</th>
</tr>
<tr>
<td><b>Ambulance Intelligence</b></td>
<td>GPS tracking only</td>
<td>Live patient vitals streaming + AI pre-routing during transit</td>
</tr>
<tr>
<td><b>Hospital Selection</b></td>
<td>Nearest hospital by distance</td>
<td>Multi-variable scored selection with full reasoning + alternatives</td>
</tr>
<tr>
<td><b>Patient Identity</b></td>
<td>Manual intake form on arrival</td>
<td>QR scan → complete medical history in 3 seconds, pre-arrival</td>
</tr>
<tr>
<td><b>Resource Data Freshness</b></td>
<td>Manual staff updates with hours of lag</td>
<td>Auto-updates via IoT geofence admission trigger — no human input</td>
</tr>
<tr>
<td><b>Smart Ambulance Cost</b></td>
<td>₹30–40 Lakhs per vehicle</td>
<td>₹1,600 IoT patch retrofits any BLS ambulance instantly</td>
</tr>
<tr>
<td><b>Unknown Unconscious Patient</b></td>
<td>No solution exists</td>
<td>Always-on lock screen + bystander SOS + encrypted QR</td>
</tr>
<tr>
<td><b>Bed Conflict Resolution</b></td>
<td>First-come-first-served</td>
<td>Triage-score priority engine — sicker patient always wins</td>
</tr>
<tr>
<td><b>Infrastructure Dependency</b></td>
<td>Proprietary, expensive systems</td>
<td>Built on OSRM, OpenStreetMap, MQTT open standards — near-zero infra cost</td>
</tr>
</table>

---

## 👥 Team

<div align="center">

| | Member | Role |
|:---:|:---|:---|
| 👨‍💻 | **Aditya Kumrawat** | Frontend Lead + OpenCV Specialist |
| 👨‍💻 | **Shreyansh Sharma** | Backend + IoT Integration |
| 👨‍💻 | **Aditya Tiwari** | ML / AI Models |
| 👨‍💻 | **Aarushi Shah** | Mobile Applications |

**Built for Prayatna 3.0 - AITR, Indore**

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=140&section=footer&text=हर%20पल,%20सही%20जाँच&fontSize=32&fontColor=fff&animation=twinkling&fontAlignY=65"/>

**HealthSaarthi** — Built with ❤️ for India's 1.4 Billion

*The right care. The right place. The right time.*

<br/>

[![GitHub stars](https://img.shields.io/github/stars/your-org/healthsaarthi?style=social)](https://github.com/your-org/healthsaarthi)
[![GitHub forks](https://img.shields.io/github/forks/your-org/healthsaarthi?style=social)](https://github.com/your-org/healthsaarthi)

</div>
