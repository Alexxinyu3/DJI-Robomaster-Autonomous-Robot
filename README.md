# DJI-Robomaster-Autonomous-Robot
This project is centered around controlling a robot using the DJI Robomaster, integrating MediaPipe and a PID controller to implement obstacle avoidance, human tracking, and object grasping functionalities on a robot. 
# Features
- Obstacle Avoidance: Real-time detection and avoidance of obstacles using sensor data.
- Human Tracking: Leverages MediaPipe to track a person’s position.
- Object Grasping: Controls a robotic arm to execute grasping tasks.
# Usage Guide
Configure: Set up the DJI SDK and ensure your robot can connect to your computer. Also, configure the MediaPipe model and related parameters.
Run: Depending on the feature you want to use, run the respective scripts:
- Obstacle Avoidance: python Obstacle_Avoidance.py
- Human Tracking: python Tracking.py
- Object Grasping: python Grab.py
- Example command: python main.py --mode obstacle
