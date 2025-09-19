# Road Toward AI for Autonomous Driving – CARLA Simulation 🚗💻

This repository documents my journey of learning **autonomous vehicle simulation and control**  
using the [CARLA simulator](https://carla.org/).  

Each notebook reflects a step in building up skills, from setting up a clean base code to implementing navigation, positioning, and multi-vehicle scenarios.

---

## 📘 Step 1 – CARLA Basics
Notebook: [`Carla_Basics.ipynb`](./Carla_Basics.ipynb)

- Started with a **clean, minimal CARLA setup**.  
- Learned how to:
  - Connect Python API to the simulator.  
  - Spawn an ego vehicle.  
  - Attach sensors (camera, lidar, etc.).  
- This became my **foundation notebook** for all later experiments.  

---

## 📗 Step 2 – Vehicle Navigation
Notebook: [`Carla_Navigation.ipynb`](./Carla_Navigation.ipynb)

- Implemented **basic navigation** for the ego vehicle.  
- Used **waypoints and autopilot commands**.  
- Learned how CARLA’s **Traffic Manager** interacts with vehicles.  
- First hands-on experience with making the car follow a desired path.  

---

## 📕 Step 3 – Positioning & Localization
Notebook: [`Carla_Positioning.ipynb`](./Carla_Positioning.ipynb)

- Focused on **vehicle positioning and localization**.  
- Extracted vehicle states:
  - Position (x, y, z).  
  - Orientation (yaw, pitch, roll).  
  - Velocity.  
- Understood how sensors and CARLA’s coordinate system are used for localization.  

---

## 📙 Step 4 – Multi-Vehicle Scenarios
Notebook: [`Carla_MultiVehicle.ipynb`](./Carla_MultiVehicle.ipynb)

- Extended from a single ego vehicle to **two or more vehicles**.  
- Implemented interactions:
  - Spawning multiple vehicles safely.  
  - Coordinating with the Traffic Manager.  
- Learned about **traffic scenarios** and preparing for urban simulations.  

---

## 🌱 Reflection – From One Car to Many
- Began with **a single ego vehicle** in a clean setup.  
- Learned **navigation** through waypoints.  
- Added **positioning and localization**, which are crucial for control.  
- Finally, worked with **multiple vehicles**, closer to **real-world traffic**.  

This progression shows my **step-by-step growth toward autonomous driving research** using CARLA.  

---

## 📂 Repository Structure
- `Carla_Basics.ipynb` → Clean foundation code (setup + ego vehicle).  
- `Carla_Navigation.ipynb` → Navigation and waypoints.  
- `Carla_Positioning.ipynb` → Positioning and localization.  
- `Carla_MultiVehicle.ipynb` → Multi-vehicle interaction and scenarios.  

---

## 🚀 How to Run
1. Install [CARLA 0.9.x](https://carla.org/).  
2. Launch CARLA server:  
   ```bash
   ./CarlaUE4.sh
