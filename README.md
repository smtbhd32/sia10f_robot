**SIA10F Robot Simulation Repository**

This repository is created to provide a comprehensive simulation of the SIA10F robot. It aims to assist fellow robotics enthusiasts, researchers, and developers in setting up and running the robot simulation efficiently. The contents include essential files for controlling the robot, defining its structure, and simulating its environment in Gazebo.

**Authors and Contributions:**
- **The Construct Team:** They provide extensive educational resources and tutorials on robotics and ROS.
- **FH Aachen - University of Applied Sciences:** Contributions related to the Motoman SIA10F simulation are derived from their projects.
- **Alberto Ezquerro Baraibar:** A leading educator in robotics, whose videos and tutorials provide valuable insights. Connect with him on LinkedIn: [Alberto Ezquerro Baraibar LinkedIn](https://www.linkedin.com/in/alberto-ezquerro-baraibar-5a7a236b/?originalSubdomain=es).

**Links:**
- **The Construct:** Visit their website for more tutorials and courses on robotics: [The Construct](https://app.theconstruct.ai/)
- **SIA10F Simulation Repository:** Explore the full repository here: [SIA10F Simulation Repository](https://github.com/MASKOR/rosin_sia10)
- **Motoman GitHub Repository:** Find more resources on the Motoman robots: [Motoman Repository](https://github.com/ros-industrial/motoman)
- **Tutorial Videos:**
  - [ROS with Industrial Robots 101+ Programming SIA10F](https://www.youtube.com/watch?v=J6Mu1P6FlxY&list=LL&index=3)
  - [ROS Q&A 143 - How to Connect MoveIt to the Actual Robot (SIA10F Simulation)](https://www.youtube.com/watch?v=edHAzfYre7E)
  - [ROSject for Motoman SIA10F](http://www.rosject.io/l/c3384a7/)

**Folder Structure:**
1. **sia10f_control:** This folder contains all the control configurations and launch files necessary for managing the movements and actions of the SIA10F robot. It allows users to set up control parameters and execute the control logic efficiently.
  
2. **sia10f_description:** This folder includes the URDF (Unified Robot Description Format) and Xacro files that define the robot's physical characteristics, including its dimensions and joints. It also contains visual meshes for the robot, which are essential for rendering in simulation environments.

3. **sia10f_gazebo:** This folder provides the Gazebo simulation environment setup. It includes the required files to simulate the SIA10F robot, as well as related models and worlds to enhance the simulation experience.

Usage:
To launch the Gazebo simulation of the SIA10F robot, follow these steps:

1. **Source Your ROS Workspace:**
   - Open a terminal and run:
     ```
     source ~/ros_ws/devel/setup.bash
     ```

2. **Start Gazebo with an Empty World:**
   - You can start Gazebo by running the following command:
     ```
     roslaunch gazebo_ros empty_world.launch
     ```

3. **Launch the Main Simulation:**
   - In a new terminal, run the following command to launch the main simulation:
     ```
     roslaunch sia10f_gazebo main.launch
     ```

4. **Interact with the Robot:**
   - You can control the robot or send commands using the appropriate ROS topics and services. Check the provided launch files and configuration settings for more details.

---
