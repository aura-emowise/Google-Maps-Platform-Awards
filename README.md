# CogniMap: Proactive Well-being Navigator

**A conceptual MVP for the Google Maps Award.**

CogniMap is a next-generation navigation concept that shifts the focus from "the fastest route" to "the optimal route for the driver's well-being." It integrates the power of the Google Maps Platform with real-time biometric data to create a proactive, human-centric navigation experience.

The core idea is a system that understands the driver's physical and mental state and **actively assists** them by suggesting calmer routes, providing cognitive analysis of the trip, and even simulating therapeutic interventions.

---

### 🚀 Live Demo

![CogniNav Pro Demo](https://github.com/aura-emowise/Google-Maps-Platform-Awards/blob/main/cognimap-demo.gif?raw=true)


A live, interactive version of this prototype is available here:

**[https://cognimap.onrender.com](https://cognimap.onrender.com)**

---

### 💡 Core Concept: From Monitoring to Intervention

This prototype demonstrates a full-cycle, human-centric system:

1.  **Biometric Monitoring:** The system simulates monitoring the driver's vital signs (Pulse, SpO2, EDA).
2.  **Proactive Assistance:** When negative changes are detected, the system suggests actions like taking a calmer route (calculated with the **Directions API**).
3.  **Active Intervention (Simulation):** A **Vagus Nerve Stimulator** is automatically activated during high-stress events, demonstrating a future where the system can actively help regulate the driver's state.
4.  **Gamification & Positive Reinforcement:** The system uses **awards** (e.g., "Calm Driver" badge) to encourage and reward safe, proactive driving behavior.
5.  **Cognitive Analysis:** At the end of the journey, the user can view a **Trip Report** summarizing all significant physiological and stress-related events, providing valuable insight into their driving habits.

---

### 🕹️ How to Use the Simulator

The interface allows you to test the full logic of the application.

1.  **Normal Mode:** The app starts in a "Normal" state with balanced vitals.
2.  **Simulate Stress (`HARD TRAFFIC / ACCIDENT`):** Activates stress vitals and the Vagus Nerve Stimulator.
3.  **Earn an Award (`ALT ROUTE`):** After a stress event, click this to get a real, on-road route and unlock the "Calm Driver" Award.
4.  **Simulate a Health Crisis (`EMERGENCY / DISEASE`):** Activates the critical health protocol and emergency countdown.
5.  **Review Your Journey (`TRIP REPORT`):** Click this to see the Cognitive Trip Analysis window with all recorded events.

---

### 🛠️ Technology Stack

This MVP is built using:
*   **HTML5, CSS3 (with Tailwind CSS), and Vanilla JavaScript**.
*   **Google Maps Platform:**
    *   **Maps JavaScript API:** For rendering the base map and custom overlays.
    *   **Directions API:** To demonstrate real-world, on-road route calculation.

This project showcases a scalable vision for the future of navigation—one that prioritizes human safety, well-being, and active assistance.```
