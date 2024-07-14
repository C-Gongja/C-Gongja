# Taeyoon Kim

## About Me
 * :computer: Software Engineer
 * :books: Interest in Software Development, AI, ML, Computer Vision

 * :school: Computer Science B.A. at UC Davis

## UC Davis F1 tenth Autonomous Race Car
F1Tenth is an autonomous racing league where universities design self-driving cars to compete for the fastest car. For our ECS Capstone project, we collaborated with Prof. Nazari's CORE Lab to develop the perception and control for the lab’s race car, enabling it to autonomously navigate a race track while avoiding obstacles, in preparation for future F1Tenth competitions.

### Perception and Controls
* Mapping (SLAM)
We use SLAM (Simultaneous Localization and Mapping) to map the track before the race. The map is used for localization and planning during the race.
* Raceline Optimization
With the map from SLAM, we generate a time optimal path around the race track using CV.
* Particle Filter
During the race, we use LiDAR scans and vehicle odometry to localize the car on the map.
* Pure Pursuit
The car is driven by a global path-tracking controller that follows the path generated by raceline optimization.
* Gap Following
When an obstacle is detected, the car switches to a local obstacle avoidance controller that steers it towards the largest open gap detected by the LiDAR.
       
[Davis RC f1tenth_stack](https://github.com/C-Gongja/darc_f1tenth_system.git) <br>
[ROS2 Simulation](https://github.com/C-Gongja/f1tenth_gym_ros.git) <br>

## AI Connect 4 
Design an AI algorithm to efficiently and competitively play the game of connect-4. <br>
Developed an AI agent for Connect 4 using the minimax algorithm (based on Q-Learning) and alpha-beta pruning to optimize game strategy and performance. <br>
Designed a graphical user interface (GUI) using Pygame, providing an interactive and user-friendly platform for playing Connect 4.

[repo](https://github.com/C-Gongja/connect_4_ai) <br>

## Youtube video controller using HGD
A YouTube Controller using hand gesture recognition, employing the MediaPipe library for Python.<br>
Use the pre-trained hand gesture detection (hgd) model that was initially developed by Kazuhito00.<br> 
Used translated version.I developed a Java-based YouTube video controller to extract outputs from a Python-based HGD and integrate them seamlessly.<br>
[repo](https://github.com/C-Gongja/hgd_youtube_controller) <br>

## Enigma Machine
The Enigma machine is a cipher device developed and used in the early- to mid-20th century to protect commercial, diplomatic, and military communication. It was employed extensively by Nazi Germany during World War II, in all branches of the German military. The Enigma machine was considered so secure that it was used to encipher the most top-secret messages. <br> -wikipedia- <br>
[repo](https://github.com/C-Gongja/Enigma-Machine) <br>

## BigNum Calculator
We often seen fixed-precision integers. For example, int64_t, uint32_t in C/C++, i64, u32 in Rust. These integers have a fixed width and a limited numbers they can represent. <br>
If the number were any larger (or smaller), the representation is incorrect. For example, in C (uint32_t) 0xffffffff + 1 == 0. <br>
This may be very in-convenient and error prone when we are carrying out large scale computations.<br>
However, integer in Python doesn't seem to have this limitation and can represent arbitrary precisions. You can calculate any integer operations without worrying the upper bound or lower bound.<br>
This caculator can computes large scale computations.<br>
[repo](https://github.com/C-Gongja/BigNum-Calculator) <br>

## Car Counting
[repo](https://github.com/C-Gongja/CV_vehicle_counter) <br>

<!--
**C-Gongja/C-Gongja** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
