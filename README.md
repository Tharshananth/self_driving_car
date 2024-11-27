Autonomous Car Using Raspberry Pi 4
Overview:
This project demonstrates an autonomous car prototype built on a four-wheel chassis using Raspberry Pi 4. 
It mimics self-driving car functionalities by navigating lanes automatically and detecting obstacles.
The system adjusts its movements based on lane tracking and obstacle detection to ensure safe navigation.
A live streaming feature is included for real-time demonstration.

Technical Approach:
Lane Tracking: Tracks the center points of lanes to guide the car's navigation.
Fine-tuned YOLOv8: A custom-trained YOLOv8 model is used for precise obstacle detection and object segmentation.
Object Analysis: Calculates object center points and divides the frames to determine safe movement paths.
Depth Mapping: Utilizes MiDaS for depth estimation, improving obstacle avoidance and path planning.
This project showcases the integration of advanced AI models and real-time decision-making for autonomous navigation.
