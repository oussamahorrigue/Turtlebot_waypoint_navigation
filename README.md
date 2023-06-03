# Turtlebot Waypoint Navigation

This project focuses on implementing waypoint navigation for the Turtlebot robot using ROS and the Turtlebot simulator. The goal is to enable the Turtlebot to autonomously navigate to a series of specified waypoints.

## Features

- Waypoint-based navigation: Define a sequence of waypoints for the Turtlebot to follow.
- PID control: Implement PID control for accurate steering and movement control.
- Odometry tracking: Use odometry data to track the Turtlebot's position and orientation.
- Visualization: Display the Turtlebot's trajectory on a plot for analysis and verification.

## Requirements

- ROS (Robot Operating System): Ensure that ROS is installed on your system.
- Turtlebot Simulator: Clone the `turtlebot_simulator` package from the official GitHub repository to simulate the Turtlebot in a virtual environment.

## Installation

1. Clone the repository:
- https://github.com/oussamahorrigue/Turtlebot_waypoint_navigation.git


2. Build the package:
- catkin_make


3. Launch the Turtlebot simulator:
- roslaunch turtlebot_gazebo turtlebot_world.launch


## Usage

1. Run the waypoint navigation script:

rosrun turtlebot_waypoint_navigation waypoint_navigation.py


2. The Turtlebot will start following the specified waypoints, pausing at each point according to the specified durations.

3. The trajectory of the Turtlebot will be saved to a `trajectory.csv` file and plotted for visualization.

## Configuration

- Adjust the waypoints and durations: Modify the `WAYPOINTS` list in the `waypoint_navigation.py` script to define your desired waypoints and durations.

- Tune PID parameters: If needed, you can tune the PID control parameters in the `PID` class to achieve better control performance.

## Contributing

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project was inspired by the Turtlebot robot and utilizes the Turtlebot simulator provided by the Open Robotics Turtlebot team.

## Contact

For any inquiries or questions, please contact [horrigueouss@{gmail.com](mailto:horrigueouss@gmail.com).
