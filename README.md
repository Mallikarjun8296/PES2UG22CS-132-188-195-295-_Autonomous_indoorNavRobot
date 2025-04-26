Project Description: Automatic Indoor Navigation System Using TurtleBot3 Waffle and Navigation2
This project simulates an autonomous indoor navigation system using the TurtleBot3 Waffle model and the Navigation2 stack in a ROS 2 environment. The primary aim is to enable the robot to autonomously explore and navigate through an indoor space with obstacle awareness and mapping capabilities.

The TurtleBot3 Waffle, known for its enhanced sensing and computing capabilities compared to other TurtleBot3 variants, is deployed in a virtual environment simulated using Gazebo, a robust 3D robotics simulator. Gazebo provides realistic physics and detailed visualization of the robot’s interaction with its environment.

For real-time monitoring and implementation, RViz is used. It visualizes data such as laser scans, maps, and robot poses, and allows users to interactively send navigation goals to the robot.

The mapping process is handled by Cartographer, a powerful SLAM (Simultaneous Localization and Mapping) system. As the TurtleBot3 Waffle navigates through the environment, Cartographer builds a 2D occupancy grid map, enabling the robot to localize itself and plan paths accurately.

This simulation demonstrates a fully functional navigation pipeline that includes:

TurtleBot3 Waffle model for high-fidelity robot simulation.

Gazebo for simulating the environment and robot physics.

Navigation2 stack for autonomous navigation, obstacle avoidance, and path planning.

Cartographer for real-time SLAM and map generation.

RViz for visualization and interactive control.

The integration of these tools provides a comprehensive framework for developing and testing autonomous indoor navigation algorithms in a simulated yet realistic environment.
