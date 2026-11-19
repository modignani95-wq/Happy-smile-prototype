# HappySmile Dental Clinic - Interactive Web Prototype

An AI-triaged dental clinic appointment and operations platform designed to streamline inbound web leads across routine hygiene, cosmetic whitening, specialist dental implants, and clear aligners/orthodontics.

---

## 🌟 Overview & Key Scenarios

The platform is designed around two connected views:

### 1. Patient's Side
* **Authentic Dental Clinic Experience:** Brand identity for **HappySmile Dental Clinic** featuring medical dental blue tones, trust indicators (4.9★ rating from 1,240+ reviews), emergency phone lines, and dental treatment overview.
* **1-Click Test Presets:** Quick buttons to autofill sample leads:
  * `Sarah` — Routine Teeth Cleaning & Polish (Same-Day Bucket A)
  * `James` — Single Dental Implant Consultation (Specialist Bucket B)
  * `Chloe` — In-Office Laser Teeth Whitening (Cosmetic Bucket A)
  * `Aiden` — Clear Aligners & Braces Consultation (Orthodontic Bucket B)
* **Smart Contact & Triage Form:** Patient enters contact details, requested service, preferred time window, and clinical symptoms.
* **Interactive AI Screening Simulation:** Triggers a quick clinical screening questionnaire (adaptive questions based on treatment) with quick-reply options.
* **Automatic Transition:** Upon completing the form and screening, the interface automatically transitions to the **Receptionist's Side** so front-desk operations can be viewed in real-time.

### 2. Receptionist's Side
* **Real-Time Synchronized Queue:** Inbound submissions immediately appear at the top of the receptionist feed with a `NEW FROM PATIENT` badge.
* **Intelligent Two-Bucket Triage:**
  * **🟢 Bucket A (Same-Day / Routine):** Fast-tracked cleaning and whitening appointments with 1-click slot confirmation.
  * **🟡 Bucket B (Specialist Consult):** Complex multi-visit procedures (implants, aligners) flagged for doctor callback and 3D imaging review.
* **Clinical Context & Staff Actions:**
  * Immediate visibility into patient notes and AI triage clinical summaries.
  * 1-click **Call Patient** simulation.
  * 1-click **Confirm Slot** action.
  * Detailed modal with WhatsApp dispatch simulation.

---

## 🚀 Getting Started

### Option 1: Direct Browser Access
Open `index.html` directly in any modern web browser. No installation or login required.

### Option 2: Run with Python Local Server
```bash
python server.py
```
Then visit **`http://localhost:8080/`** in your browser.

---

## 🛠️ Tech Stack
* **HTML5 / CSS3 / JavaScript (ES6+)**
* **React 18** (via Standalone CDN)
* **Tailwind CSS** (via CDN)
* **Plus Jakarta Sans & Inter** typography
