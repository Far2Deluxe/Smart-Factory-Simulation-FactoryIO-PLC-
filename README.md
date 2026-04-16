# 🏭 Smart Factory Automation Simulation  
### Factory I/O + Siemens TIA Portal (PLC Control)

Welcome to this **industrial automation simulation project** built using **Factory I/O** and controlled through **PLC programming in Siemens TIA Portal** using **Ladder Logic (LAD)**.

This project demonstrates a complete smart factory workflow with **sorting**, **assembly**, **warehouse storage**, and **retrieval operations**.

---

## 📌 Project Overview

The factory consists of **3 main production stages**:

### 1️⃣ Sorting Station 🎨🔷

Raw parts enter the production line and are automatically sorted based on:

- **Color**
- **Shape / Type**
  - Lids
  - Bases

Sensors detect each incoming part, and conveyors/diverters route them to their correct destinations.

---

### 2️⃣ Assembly Station ⚙️🧩

After sorting:

- Matching **lids** and **bases** are transferred to the assembly station.
- Components are aligned and assembled into final products.
- Completed units move to the next stage automatically.

---

### 3️⃣ Warehouse Matrix Storage 🏬📦

Finished products are transported into a **matrix warehouse system** where they are:

- Automatically stored in available slots
- Indexed for tracking
- Retrieved on request anytime

This simulates an automated storage and retrieval system (**AS/RS**).

---

## 🧠 Control System

The entire factory is controlled using:

### 🔌 Siemens TIA Portal
- PLC Programming using **Ladder Diagram (LAD)**
- Logic sequencing
- Sensor monitoring
- Motor / actuator control
- Warehouse indexing system

### 🏭 Factory I/O
Used for real-time industrial simulation and visualization of the factory process.

---

## 🛠️ Technologies Used

| Software | Purpose |
|--------|---------|
| 🏭 Factory I/O | Factory Simulation |
| 🔌 Siemens TIA Portal | PLC Programming |
| ⚡ Ladder Logic (LAD) | Control Logic |
| 🎛️ Sensors & Actuators | Automation Components |

---

## 📂 Repository Contents

```bash
📁 Factory-IO-SmartFactory/
│── 📄 README.md
│── 🏭 FactoryIO Scene File
│── 🔌 TIA Portal Project Files
│── 📷 Screenshots / Videos (optional)

```

## 🚀 How to Run

### Requirements

- Factory I/O installed  
- Siemens TIA Portal installed  
- PLC simulation configured (PLCSIM if needed)  

### Steps

1. Open the Factory I/O scene  
2. Open the TIA Portal project (FactoryIO_Template_S7-1200_V15_V15.1) 
3. Start PLC simulation / connect PLC (Using PLCSIM)
4. Run the ladder logic program  
5. Start Factory I/O simulation (SmartFactory_v1.6.factoryio) 
6. Watch the automated factory operate 🎉  

---

## 🎯 Features

✅ Automatic part detection  
✅ Color & shape sorting  
✅ Lid-base assembly  
✅ Conveyor automation  
✅ Smart warehouse storage  
✅ Product retrieval system  
✅ Full PLC ladder control  

---

## 📸 Preview

Add screenshots or a demo GIF here for better presentation.  

---

## 📚 Learning Objectives

This project is ideal for learning:

- PLC Programming  
- Ladder Logic Design  
- Industrial Automation  
- Material Handling Systems  
- Warehouse Automation  
- Smart Manufacturing Concepts  

---

## 🤝 Contributing

Feel free to fork this repository, improve the logic, or add HMI/SCADA integration.  

---

## 📜 License

This project is for educational purposes.  

---

## 👨‍💻 Authors

Sana'a University Students:

Fares Hilal Ahmed Haider (Mechatronics Enginner) A.NO 202270029
Luay Ahmed Yahya Zayed (Mechatronics Enginner) A.NO 202270398 
Ayman Mrwan Mohammed Al-Reazqee (Mechatronics Enginner) A.NO 202270324

---

## ⭐ Support

If you like this project, give it a star ⭐ on GitHub!