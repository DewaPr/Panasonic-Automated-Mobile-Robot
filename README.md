# Panasonic Automated Mobile Robot
This repository documents the development and deployment of an Automated Mobile Robot (AMR) at a Panasonic Manufacturing facility. The project's core challenge was to create a reliable indoor positioning and navigation system for a dynamic industrial environment.

![GIF of the AMR in action](placeholder.png)
*(A short video or GIF of the robot moving would be perfect here!)*

---

## Key Features
* **Autonomous Navigation:** Capable of point-to-point navigation and obstacle avoidance in a factory setting.
* **Indoor Positioning:** Utilizes a custom indoor positioning system based on **UWB** to achieve high-accuracy localization.
* **Task Management:** Designed to transport materials between workstations, integrating with the factory's workflow.
* **Safety System:** Equipped with a 2D LiDAR for obstacle detection, bumper sensors, and an emergency stop system.

## System Architecture
The AMR is built on a tiered hardware and software stack for robust performance.

### Hardware Stack
* **Low-Level Controller:** STM32F4 microcontroller for real-time motor control and sensor polling
* **Chassis & Drivetrain:** Differential drive with high-torque DC motors
* **Primary Sensors:** SICK TiM571 LiDAR, Wheel Encoders, UWB tags

## Project Outcome
The AMR was successfully deployed and commissioned at the Panasonic facility. It reliably transported materials, leading to an increase in operational efficiency and a reduction in manual handling tasks. But, this project cannot be continued because due to Panasonic safety standard reason.

## Project Status: **Archived**
---
*Created by [Your Name], [Year]*
