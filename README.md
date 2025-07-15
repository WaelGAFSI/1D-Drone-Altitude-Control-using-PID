# 1D-Drone-Altitude-Control-using-PID
 This project demonstrates a simple simulation of vertical (1D) altitude control for a drone using a PID (Proportional-Integral-Derivative) controller. It includes a GUI with interactive sliders for tuning `Kp`, `Ki`, `Kd`, and setting the target altitude. The simulation also includes wind disturbances to test the controller’s robustness.
@ -1,2 +1,63 @@
# 1D-Drone-Altitude-Control-using-PID
 This project demonstrates a simple simulation of vertical (1D) altitude control for a drone using a PID (Proportional-Integral-Derivative) controller. It includes a GUI with interactive sliders for tuning `Kp`, `Ki`, `Kd`, and setting the target altitude. The simulation also includes wind disturbances to test the controller’s robustness.
---

## 📸 Project Overview

<p align="center">
  <img src="image_that_manifests_my_project.png" alt="Simulation Overview" width="600"/>
</p>

<p align="center">
  <img src="Simulation-Screens.png" alt="Simulation GUI" width="600"/>
</p>

<p align="center">
  <img src="Block_diagram_of_1D_Drone_Altitude_Control_using_PID.png" alt="Block Diagram" width="600"/>
</p>

---

## ⚙️ Installation

Make sure you have **Python 3.7+** installed. Then install the required packages using:

```bash
pip install numpy matplotlib

---

## 🚀 How to Run the Project
1-Clone or download this repository to your local machine.
2-Navigate into the project folder.
3-Run the simulation file:

```bash
python drone_pid_gui.py
4-In the GUI window:
    Set the desired target altitude.
    Adjust the PID gains (Kp, Ki, Kd) using the sliders.
    Click Run Simulation to visualize the results.

---

📌 Features
    🎚️ Real-time tuning of PID controller
    🌪️ Simulated wind disturbances (random noise)
    📊 Dynamic plots for altitude, thrust, and disturbance
    🔁 Feedback loop visualization
    🧠 Educational and beginner-friendly control simulation

---

🙋 Author
Wael GAFSI
    📧 wael.gafsi@enis.tn
    📍 National Engineering School of Sfax, Tunisia
    🔗 LinkedIn (optional)

---

📄 License
This project is open-source and free to use for educational and personal use. Feel free to fork or contribute.
