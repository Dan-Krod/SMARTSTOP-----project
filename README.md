# 🚴‍♂️ SMARTSTOP - Intelligent Safety System for Electric Scooters  

## 📁 Repository Structure  

This repository contains the source code and descriptions for SMARTSTOP, an intelligent safety system designed for electric scooters. The system evolves through **three distinct prototypes**, each refining safety features such as **signalization, braking, and speed control**.

### **Directory Overview**
- **`First Prototype/`** – Basic obstacle detection and alert system  
  - `First-prototype-description.md` – Detailed explanation of the first prototype  
  - `smart_signalization_code.cpp` – Source code for the signalization system  

- **`Second Prototype/`** – Enhanced braking and obstacle detection system  
  - `Second-prototype-description.md` – Details of the second prototype  
  - `smart_breaking_code.cpp` – Source code for adaptive braking mechanisms  

- **`Third Prototype/`** – Speed control and automated obstacle response system  
  - `Third-prototype-description.md` – Description of the third prototype  
  - `smart_speed_control_automation_code.cpp` – Source code for automated speed control  

- **`README.md`** – This file, containing an overview of the project, installation, and usage instructions  

---

## 🚀 Project Overview  

SMARTSTOP is designed to improve rider safety through **real-time obstacle detection, adaptive braking, and speed control mechanisms**. The prototypes gradually integrate new technologies to ensure optimal safety and efficiency.

### **Prototype Evolution**
1. **First Prototype** – Focuses on **obstacle detection** using ultrasonic sensors, providing visual and audible alerts to riders.
2. **Second Prototype** – Introduces **adaptive braking**, combining obstacle detection with **servo-based braking assistance**.
3. **Third Prototype** – Implements **automated speed control**, integrating **multi-sensor detection**, smart braking, and obstacle response.

Future iterations will enhance **automated notifications** and **AI-powered decision-making**.

---

## ⚙️ Installation & Usage  

To use this repository, follow these steps:

### **1. Clone the repository**
```bash
git clone <repository-url>
cd SMARTSTOP-----project
```

### **2. Navigate to the desired prototype**
```bash
cd "First Prototype"
```

### **3. Compile and upload the code to an Arduino**
Use the Arduino IDE to open the `.cpp` file and upload it to the board.

### **4. Run and Test**
- Check the **LCD output** for distance measurements.
- Observe **LED indicators** for status updates.
- Listen to **buzzer alerts** for warnings.
- Test braking and speed control in the second and third prototypes.

---

## 📌 Contribution Guidelines  

If you’d like to contribute:
1. **Fork** the repository.
2. Create a **new branch** (`feature-yourname`).
3. Commit your changes with a **clear description**.
4. Submit a **pull request** for review.

---

## 🛠️ Future Plans  

SMARTSTOP will continue evolving with:
- **Automated notifications** for users.
- **Smart speed control integrated with rider behavior tracking**.

