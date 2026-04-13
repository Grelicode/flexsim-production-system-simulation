# flexsim-production-system-simulation
Discrete - event simulation of a smart factory system in FlexSim including production line, robots, ASRS warehouse and material flow optimization.

## 🚀 Overview

This project presents a discrete-event simulation of a modern production system developed in FlexSim.  
The simulated environment combines:

- automated production line  
- industrial robots  
- human operators  
- ASRS warehouse system  
- forklift-based internal transport  

The goal of the project was to analyze material flow, identify bottlenecks, and evaluate automation strategies in an integrated production and logistics system.

---

## ⚙️ System Architecture
System = Production + Robots + Operators + Warehouse + Transport
<p align="center">
<img width="1137" height="686" alt="flexsim1" src="https://github.com/user-attachments/assets/d9311c90-ff68-4047-a25e-4f9373a70ca5" />
</p>
<img width="855" height="511" alt="flexsim2" src="https://github.com/user-attachments/assets/ab630a94-d80b-42ae-9096-aec1e196234b" />
</p>

### 🏭 Production Line

- Multiple processing stations (Processor1–Processor3)  
- Buffers and queues controlling material flow  
- Parallel operations  
- Final assembly using Combiner  

---

### 🤖 Robotics

- Multiple industrial robots (Robot1–Robot7)  
- Tasks:
  - material transport  
  - machine loading/unloading  
  - routing between queues  

---

### 🧑 Operators

- Support semi-automated processes  
- Introduce realistic human constraints  

---

### 🏬 Warehouse (ASRS)

- High-bay rack system  
- Automated storage and retrieval (ASRS crane)  
- Additional manual rack area  

---

### 🚜 Transport System

- Forklift for internal logistics  
- Integration with production and storage  

---

## 🔄 System Behavior
  Dynamic interactions:
  - resource competition
  - queue buildup
  - routing logic
  - production ↔ warehouse synchronization


The model captures real industrial challenges:

- bottlenecks in queues  
- robot waiting times  
- transport delays  
- coordination between systems  

---

## 📊 What Can Be Analyzed

- Material flow efficiency  
- Resource utilization (robots, operators, forklift)  
- Bottlenecks in production and logistics  
- Impact of system configuration  

---

## 📈 Results

- Identification of system bottlenecks  
- Improved synchronization between production and warehouse  
- Reduced idle times  
- Optimized material flow  

---

## 🧠 Conclusion

```pascal
(*
  Industry 4.0 concept:
  Integration of production, automation, and logistics
*)
```

The project demonstrates how combining:

- robotics  
- warehouse automation  
- human operators  

creates an efficient and flexible smart factory system
