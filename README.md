Autonomous Car Using Raspberry Pi 4


Overview:
This project demonstrates an autonomous car prototype built on a four-wheel chassis using Raspberry Pi 4. 
It mimics self-driving car functionalities by navigating lanes automatically and detecting obstacles.
The system adjusts its movements based on lane tracking and obstacle detection to ensure safe navigation.
A live streaming feature is included for real-time demonstration

Technical Approach:
Lane Tracking: Tracks the center points of lanes to guide the car's navigation.
Fine-tuned YOLOv8: A custom-trained YOLOv8 model is used for precise obstacle detection and object segmentation.
Object Analysis: Calculates object center points and divides the frames to determine safe movement paths.
Depth Mapping: Utilizes MiDaS for depth estimation, improving obstacle avoidance and path planning.![IMG-20241126-WA0010](https://github.com/user-attachments/assets/5f841d7d-1592-439b-b86b-adcf77aecd3e)

![IMG-20241127-WA0003](https://github.com/user-attachments/assets/a60759bc-7ca6-4d33-9070-861ee225e468)
![IMG-20241127-WA0004](https://github.com/user-attachments/assets/66d286b2-6091-498a-9d7b-721660f586cc)
![IMG-20241126-WA0011](https://github.com/user-attachments/assets/6985f14e-191e-431d-9887-5b6a218958ef)![WhatsApp Image 2024-11-27 at 23 45 18_68feb05b](https://github.com/user-attachments/assets/22c4a8bf-51cb-4a40-898f-9c4cb63b7979)

![WhatsApp Image 2024-11-27 at 23 45 18_6e20584a](https://github.com/user-attachments/assets/52a2e504-96c6-4dc3-94a1-9fe97b629f90)
![WhatsApp Image 2024-11-27 at 23 45 18_0631772c](https://github.com/user-attachments/assets/4279f4ad-5fd6-4d80-bf67-17e42de63021)

https://github.com/user-attachments/assets/b5002c63-71e7-4bbe-bb1d-228515494a07


This project showcases the integration of advanced AI models and real-time decision-making for autonomous navigation.
