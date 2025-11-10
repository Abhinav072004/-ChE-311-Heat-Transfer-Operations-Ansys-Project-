# Flow Through a Mid-Rotating Section of a Pipe

## 📘 Overview
This project analyzes fluid flow and heat transfer in a pipe with a **mid-rotating section** using ANSYS Discovery/Fluent. The objective is to investigate how rotation influences the velocity field, pressure drop, and thermal performance of the system.

## ⚙️ Simulation Setup
- **Software:** ANSYS Discovery / Fluent
- **Flow Type:** Laminar, steady-state
- **Fluid:** Water
- **Pipe Material:** Stainless Steel
- **Rotating Section Material:** Aluminum Alloy
- **Rotation Speed:** 100 rad/s

## 🧩 Boundary Conditions
### Case 1: Without Rotation
- Inlet velocity: 0.2 m/s  
- Inlet temperature: 300 K  
- Wall heat flux: 5000 W/m²  
- Convective heat loss: 10 W/m²·K, ambient 20°C  

### Case 2: With Mid-Section Rotation
- Mid-section rotating wall boundary condition (100 rad/s)
- Other boundaries identical to Case 1

## 🧠 Key Assumptions
- Steady-state, incompressible laminar flow  
- Constant fluid and material properties  
- Negligible radiation  
- Linear conduction in solid walls  

## 📊 Results Summary
- Rotation enhances convective heat transfer (higher Nusselt number).  
- Maximum fluid temperature decreases with increasing angular velocity.  
- Viscous dissipation becomes noticeable at very high rotation speeds.  
- Grid independence confirmed between coarse and fine mesh cases.

## 🔍 Observations
- Enhanced mixing within the rotating section leads to improved heat removal.
- Trade-off between heat transfer and pressure drop at higher speeds.
- Recommended to combine with forced convection (external airflow) for best cooling performance.

## 🧪 Applications
- Rotating heat exchangers
- Cooling of rotating machinery (motors, turbines)
- Compact thermal management devices for chemical/thermal systems

## 📚 Author
**Abhinav Singh**  
**Jyoti Kanoje**
Department of Chemical Engineering, IIT Indore
