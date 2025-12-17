# A Low-Cost, Modular, Scalable UAV Platform for Autonomous Flight Research

This repository showcases my work on building accessible UAV platforms for autonomous flight research, highlighting some of my undergraduate research contributions at Georgia Tech’s Lunar Lab. My work focused on designing and validating a modular quadrotor platform to enable reproducible, low‑cost experimentation in autonomy and embodied AI.  

The quadrotor platform was designed around Jetson Orin NX onboard compute and Pixhawk flight controllers, with custom frames and sensor mounts to support RGB‑D, tracking, and optical flow sensors. By streamlining fabrication and integration, I reduced structural costs to under 15% of total system cost, with the remaining cost attributed to sensing and compute. The system demonstrated stable autonomous hover performance of around 15 minutes at 1.6 kg. This made it possible to scale a fleet of four UAVs at roughly one‑third the cost of comparable commercial systems.  

In the future, this work will be extended to a heterogeneous UAV–UGV platform, implementing ROS 2 vehicle‑to‑vehicle communication for distributed collaborative perception and navigation. To support testing, I developed a portable telemetry ground station for live diagnostics.

This project reflects my broader research interest in autonomy and multi‑agent systems. It strengthened my skills in CAD design (SolidWorks), embedded systems integration (Pixhawk, Jetson Orin NX), autonomy software (ROS 2, sensor fusion), and experimental validation in real-world conditions (indoor and outdoor flight tests, hover stability, static thrust-rig testing). More importantly, it demonstrates my commitment to building open, scalable platforms that lower barriers for robotics experimentation.
