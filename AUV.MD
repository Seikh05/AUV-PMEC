# 🟦 **Slide 1: Introduction**

### Title:

**Modular ROV for Seabed Mineral Exploration and In-Situ Analysis**

### Content:

* Increasing demand for:

  * Rare earth elements (REEs)
  * Cobalt, Nickel, Titanium
* Deep sea remains largely unexplored
* Current systems:

  * Expensive
  * Non-modular
  * Limited in-situ analysis

---

### Key Line:

> “This project proposes a modular, cost-effective ROV system for underwater mineral detection, sampling, and preliminary analysis.”

---

# 🟥 **Slide 2: Problem Statement**

### Problems:

* Lack of **low-cost exploration systems**
* Inefficient sampling (gripper OR suction, not both)
* No onboard **real-time analysis** in budget systems
* Difficulty operating at increasing depths

---

### Gap:

> No integrated system combining **sampling + analysis + scalability**

---

# 📚 **Slide 3: Literature Review**

### 🔹 Existing ROV Systems:

* Use:

  * Thrusters
  * Cameras
  * Manipulators
* Limitations:

  * Single-mode sampling
  * High cost

---

### 🔹 Hybrid Grippers:

* Combine:

  * Mechanical gripping
  * Vacuum suction
* Improve flexibility and precision
  (From hybrid micro-gripper research)

---

### 🔹 Control Systems:

* Advanced control needed for underwater systems
* Robust methods like nonlinear control improve stability

---

### Key Insight:

> Need for **flexible, modular, multi-functional systems**

---

# 💡 **Slide 4: Proposed Design**

### Title:

**Modular Depth-Adaptive ROV Architecture**

---

### System Includes:

* Hybrid manipulator
* Sensor fusion system
* Pressure-balanced electronics
* Modular design

---

### Innovations:

* Hybrid claw + suction system
* Low-cost in-situ analysis
* Depth-based mission strategy

---

# ⚙️ **Slide 5: Mechanism (Core USP)**

### Title:

**Tri-Actuator Parallel Hybrid Manipulator**

---

### Description:

* 3 linear actuators
* Single fused end-effector
* End-effector:

  * Gripper (for nodules)
  * Suction (for fine particles)

---

### Modes:

* Grasping
* Suction
* Hybrid (USP 💥)

---

### Line:

> “Combines mechanical and fluid-based sampling in a single compact system.”

---

# 🧪 **Slide 6: Sampling & Analysis System**

### Workflow:

Detect → Approach → Collect → Analyze → Store

---

### Sensors:

* Camera → visual analysis
* NIR spectrometer → mineral signature
* Magnetometer → metal presence
* Load cell → hardness

---

### Important:

> “Performs preliminary classification, not full chemical analysis.”

---

# 🌊 **Slide 7: Pressure System**

### Title:

**Pressure Balanced Oil-Filled System (PBOF)**

---

### Concept:

* Electronics submerged in dielectric silicone oil
* External pressure = internal pressure

---

### Camera Module:

* Titanium Grade 5 housing
* Sapphire viewport
* 1 atm internal pressure

---

### Note:

* Pressure compensator (future addition)

---

# 🧭 **Slide 8: Navigation System**

### Sensors:

* IMU → motion
* Magnetometer → orientation
* Depth sensor → vertical control
* SONAR → mapping

---

### Positioning:

* Surface GPS + tether estimation
* Acoustic positioning (future)

---

### Line:

> “Sensor fusion using EKF ensures stable underwater navigation.”

---

# 💻 **Slide 9: Software Architecture**

```
Operator → ROS2 → MAVLink → Actuators  
Sensors → ROS2 → ML → Feedback
```

---

### Features:

* Real-time control
* Sensor fusion
* ML-based classification

---

# 🌐 **Slide 10: Communication System**

### Primary:

* Tether (wired/fiber optic)

### Backup:

* Acoustic communication (future)

---

# 🌊 **Slide 11: Depth-Based Strategy**

### 0–200 m:

* Full system operation
* Sampling + analysis

---

### 200–1000 m:

* Improved sensing
* Partial sampling

---

### >4000 m:

* Detection only
* Target:

  * REE sediments
  * Gas hydrates

---

### Line:

> “System adapts based on depth and operational constraints.”

---

# ⚙️ **Slide 12: Components Required**

### Mechanical:

* Linear actuators
* Frame (Aluminum/SS)
* Sealing (O-rings, Viton)

---

### Sensors:

* Camera
* SONAR
* IMU
* Depth sensor
* NIR spectrometer

---

### Electronics:

* Jetson Nano
* Microcontroller
* Motor drivers

---

### Others:

* Pump (suction system)
* Tether cable

---

# 💰 **Slide 13: Budget (Approx)**

| Component        | Cost       |
| ---------------- | ---------- |
| Frame            | Low        |
| Thrusters        | Medium     |
| Camera           | Medium     |
| NIR Spectrometer | Exp ⚠️     |
| SONAR            | Exp ⚠️     |
| DVL              | Very Exp ❌ |
| USBL             | Very Exp ❌ |
| Jetson Nano      | Medium     |
| Titanium housing | ₹20k–₹33k  |

---

### Add:

* Use alternatives for costly sensors
* Modular upgrade path

---

# 🚧 **Slide 14: Challenges & Open Problems**

* Deep-sea pressure resistance
* Sample transfer without water
* Sensor calibration underwater
* High-cost components

---

### Line:

> “These challenges define future research directions.”

---

# 🎯 **Slide 15: Conclusion**

### Summary:

* Modular ROV system proposed
* Hybrid sampling mechanism
* Low-cost analysis approach
* Scalable depth strategy

---

### Final Line (Important):

> “The proposed system bridges the gap between low-cost prototyping and scalable deep-sea exploration technologies.”

---


