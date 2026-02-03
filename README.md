# 🚁 Autonomous Drone Fleet Simulation

## 📌 Project Overview
The **Autonomous Drone Fleet Simulation** is a visualization-focused project that demonstrates the behavior of multiple autonomous drones operating in a shared environment. The system simulates drone movement, task assignment, obstacle avoidance, collision handling, and performance metrics in real time.

This project primarily focuses on the **Visualization and User Interface module** of a larger autonomous drone system, serving as a front-end representation of simulation logic that can later be integrated with a C++ backend.

---

## 🎯 Objectives
- Visualize multiple drones moving simultaneously in a 2D environment
- Display real-time drone telemetry (position, velocity, acceleration)
- Represent task assignment and completion status
- Demonstrate collision avoidance and obstacle handling
- Show performance metrics such as FPS, speed, and simulation time

---

## 🧩 System Modules (Visualization Perspective)

### 1. Drone Visualization
- Drones are displayed as triangular entities
- Orientation reflects direction of motion
- Color changes indicate collision or obstacle avoidance

### 2. Task Representation
- Tasks are logical roles assigned to drones
- No physical task objects are placed in the environment
- Task status is displayed in the UI panel

### 3. Obstacle Avoidance
- Obstacles are shown as static red circles
- Drones dynamically adjust paths to avoid collisions
- Avoidance behavior is visually observable

### 4. Performance Metrics
- Total number of drones
- Average drone speed
- Collision event count
- Simulation runtime
- Frames Per Second (FPS)

---

## 🖥️ Technologies Used
- **HTML5** – Canvas rendering and UI structure
- **CSS3** – Styling and layout
- **JavaScript** – Simulation logic, animation loop, and data handling

> ⚠️ Note: This project currently uses **embedded JavaScript and CSS** within a single HTML file for simplicity.

---

## ▶️ How to Run the Project
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The simulation will start automatically

*(No server or external dependencies required)*

---

## 📊 Output Features
- Real-time animated drone movement
- Telemetry overlay for each drone
- Transparent UI dashboard
- Visual collision indicators
- Task completion updates

---

## 🚀 Future Enhancements
- Integration with real C++ simulation backend
- 3D visualization using WebGL
- Advanced path-planning algorithms
- Dynamic task reassignment
- Real-time sensor data integration

---


