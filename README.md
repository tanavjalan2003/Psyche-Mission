# README

# 🚀 Psyche 1825 – Orbital of a Metal World  
An interactive 3D simulation bringing asteroid Psyche to life through immersive orbital and surface experiences.

---

## 📌 Overview  
**Psyche 1825 – Orbital of a Metal World** is an interactive simulation developed at Arizona State University (ASU) in collaboration with NASA Jet Propulsion Laboratory (JPL) and the NASA Psyche Mission.

The project visualizes a **year on asteroid Psyche (16 Psyche)**—a unique metal-rich celestial body—by combining scientific accuracy with an engaging user experience. Users can explore both orbital and surface perspectives, experiencing Psyche’s fast rotation, long orbital period, and metallic terrain in real time.

---

## ✨ Features  

- 🌌 **Dual Simulation Views**
  - Orbital View: Explore Psyche’s motion in space  
  - Surface View: Experience ground-level perspective  

- ⏱️ **Time Simulation Controls**
  - Adjustable time flow (fast-forward / rewind)  
  - Realistic day-night cycle (~4h 12m per day)  
  - Full orbital year simulation (~1828 Earth days)  

- 🛰️ **Scientific Visualization**
  - Orbital paths and planetary motion  
  - Temperature mapping  
  - Realistic asteroid rotation and geometry  

- 🎮 **Interactive UI**
  - Play, pause, reset controls  
  - Camera navigation and fullscreen support  
  - Smooth and responsive experience  

- 🌍 **Educational Purpose**
  - Built for students, educators, and space enthusiasts  
  - Bridges real NASA mission data with interactive learning  

---

## 🛠️ Technologies Used  

- JavaScript  
- React.js  
- Three.js  
- HTML / CSS  
- GLB 3D Models (Psyche, Earth, Sun)

---

## 📂 File Structure  
```bash
psyche-simulation/
│
├── public/
│ ├── Simulation_OrbitalView.html
│ ├── Simulation_SurfaceView.html
│ ├── psycheModel.glb
│ ├── Earth.glb
│ ├── sun.glb
│ └── assets/
│
├── src/
│ ├── components/
│ │ ├── Home.js
│ │ ├── About.js
│ │ ├── SimulationDetails.js
│ │ ├── FAQs.js
│ │ ├── Contact.js
│ │ ├── Header.js
│ │ ├── Footer.js
│ │ └── FeedbackForm.js
│ │
│ ├── App.js
│ ├── index.js
│ ├── styles.css
│ └── App.css
│
├── Asteroid.js
├── index.html
├── manifest.json
└── README.md
```
---

## 🎥 Output  

- Interactive browser-based simulation  
- Orbital and surface visualization of asteroid Psyche  
- Real-time simulation controls  

🔗 Demo Videos:  
- https://www.youtube.com/watch?v=FrwgDXYoUEc  
- https://www.youtube.com/watch?v=dqEgZu-gvNQ  

---

## ⚙️ Setup Instructions  

### 1. Clone the Repository  

Download the project files by cloning this repository.

- **Mac and Linux**: Open a terminal, navigate to the folder where you want to save the project, and type:

```bash
git clone <repository-url>
```
Windows: Open Command Prompt or PowerShell, navigate to the folder where you want to save the project, and type:
git clone <repository-url>

Replace <repository-url> with the URL of this repository.


2. Navigate to the Project Folder

Move to the project folder using the following command:
Mac and Linux:
```bash
cd psyche-simulation
```
Windows:
```bash
cd psyche-simulation
```

📦 3. Install Dependencies

Run the following command in the project folder:
```bash
npm install
```
This command will download and install all the dependencies listed in the package.json file. It may take a few minutes.

🚀 4. Start the Project

Once the installation is complete, you can start the project by running:
```bash
npm start
```
This will open the project in your default web browser. If it doesn’t open automatically, you can open your browser and go to:

http://localhost:3000/Home


▶️ How to Use
Launch the simulation in your browser
Choose between Orbital View or Surface View
Use controls to:
Play / Pause simulation
Adjust time speed
Reset camera
Toggle views and overlays


🎨 Customization Guide
Modify Simulation Behavior
Update logic inside Asteroid.js
Extend Features
Add new components inside /src/components
Improve Visuals
Replace .glb models for higher fidelity
Enhance lighting and textures in Three.js


🙌 Acknowledgments

Developed as part of the CSE 485/486 Capstone Course at Arizona State University (ASU).

Student Team
Luz Rodriguez
Melody Musmacker
Luka Micevic
Akshay Pasumarthi
Tanav Jalan

Academic Guidance
Prasad Mahalpure
Jagruth Arutla

Special thanks to:
NASA
NASA Jet Propulsion Laboratory (JPL)
Psyche Mission Team

📬 Contact
📧 tjalan@asu.edu
