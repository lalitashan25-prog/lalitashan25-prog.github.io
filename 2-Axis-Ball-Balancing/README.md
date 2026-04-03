# 2-Axis Ball Balancing Robot

## Project Overview
This project involved the collaborative design and implementation of a closed-loop electromechanical system designed to continuously balance a ball on a dynamic surface. The core challenge was achieving stable position holding despite external physical disturbances, demonstrating practical applications of control theory in hardware.

## Implementation Details

### Collaborative Hardware & Software Integration
Working closely as part of an engineering team, we built the physical balancing platform and developed the core control logic using **Arduino C++** firmware. The system utilizes real-time sensor feedback to continuously monitor the ball's position on the platform.

### PID Controller Tuning
The most critical phase of the project was the hands-on control engineering. We designed and meticulously hand-tuned a **PID controller** to manage the stabilization loop. By iteratively adjusting the Proportional, Integral, and Derivative gains as a team, we successfully calibrated the system to actuate the motors with precision, keeping the ball perfectly stabilized at the target set-point.

## Hardware Demonstration

*(Watch our tuned PID system in action below)*

<video src="Two_axis_ball_balancing.mp4" width="350" controls></video>

---
*Note: The core Arduino firmware and PID tuning parameters are kept private, but are available for review upon request.*
