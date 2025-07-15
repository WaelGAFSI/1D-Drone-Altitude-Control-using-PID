# 1D-Drone-Altitude-Control-using-PID
 This project demonstrates a simple simulation of vertical (1D) altitude control for a drone using a PID (Proportional-Integral-Derivative) controller. It includes a GUI with interactive sliders for tuning `Kp`, `Ki`, `Kd`, and setting the target altitude. The simulation also includes wind disturbances to test the controller’s robustness.
@ -1,2 +1,63 @@
# 1D-Drone-Altitude-Control-using-PID
 This project demonstrates a simple simulation of vertical (1D) altitude control for a drone using a PID (Proportional-Integral-Derivative) controller. It includes a GUI with interactive sliders for tuning `Kp`, `Ki`, `Kd`, and setting the target altitude. The simulation also includes wind disturbances to test the controller’s robustness.
---

## 📸 Project Overview

<p align="center">
  <img src=""https://github.com/user-attachments/assets/34acaa4e-2e51-45f5-9555-19bc7b4c0db5" alt="Simulation Overview" width="600"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/57dc8a75-63f0-4abf-8837-27aca9639465" alt="Simulation GUI" width="600"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/73bf6b60-a504-4fd9-8df9-6b83be26e09c" alt="Block Diagram" width="600"/>
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
