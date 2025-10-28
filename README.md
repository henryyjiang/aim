# trafficprogram
Traffic direction code can be viewed in the "trafficprogram" file.
Self-driving car code is in the "cv2curve" file.
### Background
This AIM is proposed as a system that integrates self-driving cars, allowing them to share lidar and detection data with each other, and also leverages the system to detect the positions of vehicles to improve the efficiency of traffic direction.

Reinforcement learning was chosen as the algorithm, and the Q-values of adjacent intersections are taken into consideration when making a decision, referred to as "Double Q-Learning" as this system was modeled with only two intersections. The following demonstrates the effectiveness of double Q-learning, with a bar for the left and right intersections respectively. At best, double Q-learning was 40% more efficient than the control.


To expand on this project, a simple self-driving vehicle was built and integrated into the software operating on ultrasound and pathfinding via heuristic. The following image demonstrates the view of the robot and calculation of how much to turn (number in bottom right).
![Alt text](images/Screenshot 2024-05-05 133039.png)
![Alt text](images/Screenshot 2025-10-27 211807.png)
