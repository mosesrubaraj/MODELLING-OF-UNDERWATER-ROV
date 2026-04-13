# 🌊 Modelling of Underwater ROV

![Fusion 360](https://img.shields.io/badge/Fusion%20360-CAD%20Design-orange)
![SolidWorks](https://img.shields.io/badge/SolidWorks-Structural%20Analysis-red)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> Design and structural analysis of a turtle-inspired autonomous ROV for underwater inspection. Developed in Fusion 360 and SolidWorks, the vehicle is built for ocean floor navigation and monitoring, validated against pressure, collision, and buoyancy requirements.

---

## 📐 Key Specifications

| Parameter | Value |
|-----------|-------|
| Max Operating Depth | 100 metres |
| Max Pressure Rating | 10 bar |
| Safety Factor | 8 |
| Load Capacity | 20 kg |
| Thrust per Motor | 5 kg |
| Number of Thrusters | 5 |
| Frame Material | HDPE |

---

## 🛠️ Tools & Methods

**Fusion 360** — 3D modelling, assembly design, and motion configuration.

**SolidWorks** — Structural and pressure analysis under operational and worst-case loading conditions.

---

## 🔄 Project Flowchart

![image](https://github.com/user-attachments/assets/4560b306-a956-4b6d-88e3-0d841c03d3ca)

---

## 🐢 Turtle-Inspired Design

![image](https://github.com/user-attachments/assets/69d36a02-2bbd-4d6c-a2cb-7d078e265f04)

The ROV takes design cues from turtle anatomy — a compact, closed-frame cylindrical body that houses all key electronics (batteries, microcontrollers, sensors, communication module) in a protected enclosure.

**Thruster configuration:**

| Thruster | Count | Function |
|----------|-------|----------|
| Vertical | 2 | Up / down movement |
| Horizontal (adjustable) | 2 | Forward, backward, lateral, rotational |
| Additional | 1 | Stability and precision manoeuvring |

The closed frame design provides impact resistance throughout, with five thrusters enabling full 6-DOF control in confined underwater environments.

---

## 🔩 Structural Analysis

![image](https://github.com/user-attachments/assets/80f693d2-1e2f-49de-960b-2daebd09fd8b)

**Pressure & Collision:**
- Rated to withstand 10 bar, with a safety factor of 8 at 100 m depth
- Collision tests confirm high durability at frame edges
- Minor deformation risk identified near thruster connection points at maximum depth — potential leakage point flagged for design refinement

**Buoyancy:**
- Model buoyancy supports up to 20 kg payload
- Neutral buoyancy achieved using rigid polyurethane foam to offset heavier components

**Material Selection:**

| Material | Corrosion Resistance | Weight | Verdict |
|----------|---------------------|--------|---------|
| Stainless Steel | Low | Heavy | Rejected |
| Aluminium | Low | Medium | Rejected |
| Polypropylene | High | Light | Considered |
| HDPE | High | Light | ✅ Selected |

HDPE was selected for the frame due to its corrosion resistance, low weight, ease of machining, and proven performance in marine environments.

---

## 📊 Key Outcomes

- Turtle-inspired closed-frame geometry provides structural resilience and compact electronics housing
- Safety factor of 8 at 100 m confirms robust pressure rating for inspection-class deployments
- HDPE outperformed metallic alternatives for the frame — corrosion-free, lightweight, and machinable
- Thruster arrangement enables full manoeuvrability in restricted underwater spaces
- Minor vulnerability identified at thruster connection joints under maximum depth loading — recommended area for further structural optimisation

---

## 👤 About

**Moses Rubaraj** — BEng Mechatronics | MSc Robotics & Automation, University of Salford

[![GitHub](https://img.shields.io/badge/GitHub-mosesrubaraj-black?logo=github)](https://github.com/mosesrubaraj)
