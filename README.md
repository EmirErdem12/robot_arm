# Robotic Arm Design & Control 🦾

<img width="594" height="585" alt="image" src="https://github.com/user-attachments/assets/30e035fb-4876-48bc-9233-e8d9f79998d0" />


## 📌 About the Project
This project involves the complete mechanical design, electronic integration, and software development of a 4-DOF robotic arm. The system was engineered from scratch to perform pick-and-place tasks and serves as a comprehensive demonstration of mechatronic system integration.

## ⚙️ Technologies & Tools
* **CAD Design & Simulation:** SolidWorks
* **Manufacturing:** Creality Ender 3 V3 CoreXZ (FDM 3D Printing)
* **Microcontroller / Brain:** PIC16F887
* **Actuators:** MG996R and MG90S Servo Motors
* **Programming Language:** C 

## 🛠️ Mechanical Design & Kinematics (CAD)
The structural components were designed in SolidWorks to ensure structural integrity while minimizing weight. Forward and inverse kinematics were considered during the dimensioning phase to achieve the desired workspace and payload capacity.

<img width="621" height="558" alt="image" src="https://github.com/user-attachments/assets/ebe43bb7-9776-4484-94f4-59dae69f34bd" />


## ⚡ Electronics & Control System
The core of the control system is based on an PIC16F887 microcontroller. The electronic architecture includes motor drivers, a dedicated power supply unit, and appropriate wiring to handle the current drawn by the actuators during dynamic movements.

<img width="1052" height="551" alt="image" src="https://github.com/user-attachments/assets/aa8f64ba-05ba-4411-b021-5d67692a08d2" />
<img width="510" height="688" alt="image" src="https://github.com/user-attachments/assets/e2e3cdc3-c67c-4077-b261-4832583f8e28" />
<img width="510" height="688" alt="image" src="https://github.com/user-attachments/assets/54e06950-e73b-40c2-bbea-ecbcba78d460" />


## 🖨️ Manufacturing & Assembly
Custom joints, linkages, and the base structure were 3D printed. Mechanical assembly required precise tolerancing for bearings and motor shafts to eliminate backlash and ensure smooth operation.

## 📂 Repository Structure
* `CAD_Files_Step/` : SolidWorks part and assembly files (.sldprt, .sldasm)
* `Code/` : Microcontroller source code for kinematics and motor control
* `STL_Files/` : 3D printable models (.stl)
