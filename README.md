# 🚀 Rocketpath — Rocket Trajectory Simulation Tool

A desktop-based rocket trajectory simulator built using **Python**, **Tkinter**, and **Matplotlib**, designed to help students, hobbyists, and aerospace enthusiasts quickly visualize and analyze basic rocket flight dynamics.

This tool simulates altitude, velocity, total impulse, thrust-to-weight ratio, and more while offering **real-time trajectory animation**, **performance metrics**, and **CSV export** for deeper analysis.

---

## ✨ Features

### 🎯 Trajectory Simulation
- Real-time altitude vs. time animation  
- Rocket motion marker during flight  
- Automatic velocity vs. time graph  

### 📊 Performance Metrics
Includes the calculation of:
- Max altitude  
- Max velocity  
- Total flight time  
- Average velocity  
- Thrust-to-weight ratio  
- Total impulse  
- Propellant mass  
- Mass flow rate  
- Specific impulse  

### 📁 Data Export
Export simulation results to **CSV**, including:
- Time series  
- Altitude data  
- Performance metrics  

---

## 🖥️ GUI Overview

The Tkinter interface provides:
- Input fields for **Mass (kg)**, **Thrust (N)**, **Burn Time (s)**
- Buttons:
  - Run Trajectory Simulation  
  - Display Performance Metrics  
  - Save Simulation Data  
  - Reset Inputs  
- Smooth hover effects  
- Clean light theme  

---

## 📦 Installation

### 1. Clone the repository

git clone https://github.com/yourusername/rocketpath.git
cd rocketpath

2. Install dependencies
pip install numpy matplotlib pandas


(Tkinter comes bundled with most Python installations. If missing, install it based on your OS.)

▶️ Running the Application

Start the GUI:

python rocketpath.py


A window opens where you can input parameters and start simulations.

📚 Project Structure
Rocketpath/
│
├── rocketpath.py        # Main program
├── README.md            # Documentation
└── assets/              # (Optional) Screenshots or media

🧪 Example Inputs

Try these for a quick test:

Mass: 5 kg

Thrust: 300 N

Burn Time: 3 s

Outputs include:

A smooth trajectory animation

Velocity plot

Full performance metrics summary

🛠️ Future Improvements

Potential upgrades:

Aerodynamic drag

Multi-stage rockets

Throttle curves

Atmospheric density effects

3D trajectory visualization

🤝 Contributing

Want to improve the physics, optimize the simulation, or enhance the UI?
Feel free to fork the repo, make changes, and submit a pull request!

📄 License

Licensed under the MIT License.
