<p align="right">
  <img src="https://image2url.com/images/1764000126794-4245c613-7490-44f1-a00c-c440e9a4a2a7.png" alt="Logo" width="240"/>
</p>
# Bidirectional AI Person Counter

This repository serves as the development platform for **Bidirectional AI Person Counter**, a project primarily created and owned by **Rohit Raj**.

---

## ✨ Project Overview

This project is a comprehensive **AI-integrated control system** designed to **monitor, tally, and dynamically manage lighting and electronic equipment** in partitioned spaces. The system utilizes sensor logic and an embedded rule-based AI for high-reliability people counting and automated room management.

### Core Functionality:
* **Bidirectional Counting Logic:** Determines movement direction (Entry/Exit) by monitoring the sequential trigger across two IR sensors (IR1 → IR2 for Entry; IR2 → IR1 for Exit).
* **Rule-based AI & Control:** The entire system logic is implemented as a custom, highly efficient **rule-based AI** in C++ running on the microcontroller. This handles all counting, system state management, and adaptive control processes.
* **System Integration & Adaptive Control:** The count and direction data are fed into the embedded system which autonomously controls lights and electronics based on complex, user-defined rules. The system supports 3 operational modes and 4 room size configurations, toggleable via a 4-bit switch interface.

### 💡 Operational Modes:
1.  **Discipline Room Partition:** Automated light control to designate specific seating areas, ensuring focused use (e.g., study room).
2.  **Open Room Partition:** Uniform brightness-controlled lighting suitable for communal or hall areas, adjustable by user requirement.
3.  **Closed Room Partition:** Supports assigned, private areas, requiring **biometric verification** for entry and allowing personalized manual light control within the zone.

### Key Technologies:
* **Programming Language & Logic:** C++ for implementing the core rule-based AI logic.
* **Microcontroller/Processing Unit:** **Arduino** (or compatible board) for handling the sensor inputs and executing the embedded system logic.
* **Sensor Layer:** IR Sensors (IR1, IR2)

---

## 🤝 Collaboration & Exhibition Status

This project is the official submission of **Rohit Raj**.

* **Primary Owner & Presenter:** Rohit Raj
* **My Role (Ayush Jain - Repository Owner):** I contributed to the technical development (e.g., specific modules, testing, code review) as a supportive collaborator. **My contributions were developed using AI-assisted tools, such as Gemini, as I do not have a background in C++.**
* **Exhibition Status:** I, Ayush Jain, am **not** a participant in the official exhibition, presentation, or any formal judging related to this project. My role is strictly supportive of the development effort for Rohit Raj.

---

## ⚙️ Getting Started

### Software Setup
1.  Download and install the **Arduino IDE**.
2.  Install any specific libraries required by the C++ code (e.g., for biometric sensor integration).
3.  Upload the Arduino sketch (`.ino` file) to the microcontroller.

### Hardware Setup
Hardware components and detailed wiring instructions will be provided in a separate document (e.g., `HARDWARE.md` or a wiki page).
