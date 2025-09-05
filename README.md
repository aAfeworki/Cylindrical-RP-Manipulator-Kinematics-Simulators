# Cylindrical-RP-Manipulator-Kinematics-Simulators
Interactive Python-based simulators for the Cylindrical RP (Revolute–Prismatic) manipulator, including forward kinematics with slider control, forward kinematics driven by inverse kinematics solutions, and an inverse kinematics simulator.



This repository provides interactive simulators for the Cylindrical RP (Revolute–Prismatic) Manipulator, implemented in Python using `matplotlib`.  
It demonstrates both forward and inverse kinematics, offering intuitive visualizations to explore the motion of cylindrical manipulators.  



🚀 Features
- Forward Kinematics (Slider-Controlled)
  Control the manipulator interactively by adjusting the revolute joint angle and prismatic joint displacement with sliders.  

![image alt](https://github.com/aAfeworki/Cylindrical-RP-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_Cylinderical_RP_manipulator_with_Slider.png?raw=true)

- Forward Kinematics (IK-Driven)
  Drive the manipulator using joint variables (angle and displacement) calculated from the inverse kinematics solver.  

![image alt](https://github.com/aAfeworki/Cylindrical-RP-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_Cylinderical_RP_Industrial_Robot.png?raw=true)

- Inverse Kinematics Simulator
Enter the equation of a curve on the User Interface to generate joint angles that position the manipulator’s end-effector.

  ![image alt](https://github.com/aAfeworki/Cylindrical-RP-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_Cylinderical_RP_manipulator_with_Simulator.png?raw=true)

 ![image alt](https://github.com/aAfeworki/Cylindrical-RP-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_Cylinderical_RP_manipulator_with_Simulator%20User%20Interface.png?raw=true)

📂 Project Structure

Cylindrical-RP-Manipulator-Kinematics-Simulators
      FK_Simulator_for_Cylinderical_RP_manipulator_with_Slider.py
      FK_Simulator_for_Cylinderical_RP_Industrial_Robot.py
      IK_Generator_for_Cylinderical_RP_manipulator_with_Simulator.py
      README.md



🛠 Requirements
- Python 3.12
- `numpy`
- `matplotlib`
- `tkinter`




▶️ Usage
Run any simulator with:

      FK_Simulator_for_Cylinderical_RP_manipulator_with_Slider.py

      FK_Simulator_for_Cylinderical_RP_Industrial_Robot.py

      IK_Generator_for_Cylinderical_RP_manipulator_with_Simulator.py


🎯 Applications

      Educational tool for learning the kinematics of cylindrical RP manipulators.


      Useful for robotics students, educators, and researchers.


      A starting point for further work on dynamics, control, and trajectory optimization.


📜 License
This project is licensed under the MIT License.

👨‍💻 Developed by Afework Alemu
