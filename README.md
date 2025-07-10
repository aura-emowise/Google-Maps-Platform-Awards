
Due to the tragedy in Texas, the application has been supplemented and revised. 
The updated video is here https://youtu.be/uRZKOCI2AXM. 
The link to the code is here: https://github.com/aura-emowise/UPD-Google-Maps-Platform-Awards.git
DEMO link Live (https://upd-google-maps-platform-awards.onrender.com)







# Cogni MAP: The Geo-Mental Navigator of the Future



**Conceptual MVP for the Google Maps Award.**


Cogni MAP is a next-generation navigation concept that shifts the focus from the “fastest route” to the “optimal route for driver well-being.” It combines the power of the Google Maps platform with real-time biometric data to create a proactive, human-centric navigation experience.

The core idea is a system that understands the physical and mental state of the driver and **actively assists** them by suggesting calmer routes, providing cognitive analysis of the trip.



---

### 🚀 Live Demo

A live, interactive version of this prototype is available here:

**[https://aura-emowise.github.io/Google-Maps-Platform-Awards/](https://aura-emowise.github.io/Google-Maps-Platform-Awards/)**

---

### 💡 Basic Concept: From Monitoring to Intervention

This prototype demonstrates a complete, human-centric system:

1. **Biometric Monitoring:** The system simulates monitoring of the driver's vital signs (heart rate, SpO2, EDA).

2. **Proactive Assistance:** When negative changes are detected, the system suggests actions, such as choosing a calmer route (calculated using the **Directions API**).

3. **Active Intervention (Simulation):** The **Vagus Nerve Stimulator** is automatically activated during stressful events, illustrating a future where the system can actively help regulate the driver's state.

4. **Gamification and Positive Reinforcement:** The system uses **rewards** (such as the "Calm Driver" badge) to encourage and reward safe, active driving behavior.

5. **Cognitive Analysis:** At the end of the trip, the user can view a **Trip Report** that summarizes all significant physiological and stressful events, providing valuable insight into their driving habits.

---

### 🕹️ How to Use the Simulator

The interface allows you to test all the logic of the application.

1. **Normal Mode:** The application starts in a "normal" state with balanced vital signs.

2. **Simulate Stress (`HARD TRAFFIC / ACCIDENT`):**
* Tap to simulate a stressful event.
* **Watch:** Vital signs deteriorate and the **Vagus Nerve Stimulator** status changes to `ON`. The stressful route is displayed on the map.

3. **Receive Reward (`ALTERNATIVE ROUTE`):**
* After a stressful event, tap `ALTERNATIVE ROUTE`.
* **Watch:** A realistic road route is calculated. This safe choice will earn you the **Calm Driver** reward, which will appear on your dashboard.

4. **Simulate a Health Crisis (`EMERGENCY / ILLNESS`):**
* This button simulates a critical health event by activating the VNS and the emergency protocol with a 10-second countdown to a simulated 911 call.

5. **Review Your Trip (`TRIP REPORT`):**
* After some events, press this button.
* The **Cognitive Trip Analysis** window will appear, showing a log of all stressful, critical, and recovery events that occurred during the simulated trip. This is a key feature for user self-reflection.

6. **Operation Log (LOGS):**
* The bar at the bottom of the map shows the internal "thoughts" of the system for technical demonstration purposes.

---

### 🛠️ Tech Stack

This MVP is built using:
* **HTML5, CSS3 (with Tailwind CSS), and Vanilla JavaScript**.
* **Google Maps Platform:**
* **Maps JavaScript API:** For rendering the base map and custom overlays.
* **Directions API:** For demonstrating real-world route calculation on the road.

This project demonstrates a scalable vision for the future of navigation that prioritizes human safety, well-being, and proactive assistance.
