<h1 align="center">UCU Space Robotics 🇺🇦</h1>

<p align="center">
  The first Ukrainian team competing at the <a href="https://roverchallenge.eu/">European Rover Challenge</a> —
  building <b>Indomitus</b>, a Mars rover equipped with a robotic arm and a drone, at the
  Ukrainian Catholic University for ERC 2026.
</p>

<p align="center">
  <a href="https://indomitus-ucu.vercel.app/">Website</a> ·
  <a href="mailto:indomitus@ucu.edu.ua">Email</a> ·
  <a href="https://www.instagram.com/indomitus.ucu/">Instagram</a> ·
  <a href="https://www.facebook.com/people/Indomitus-Ucu/61588639040416">Facebook</a> ·
  <a href="https://www.linkedin.com/in/ucu-space-robotics-1664a23b7/">LinkedIn</a> ·
  <a href="https://www.tiktok.com/@ucu.space.robotics">TikTok</a>
</p>

---

## What we're building

We're a team of students building Indomitus, a Mars rover, as one system: an onboard ROS 2 stack,
a robotic arm, a drone, embedded firmware across a dozen microcontrollers, and the ground station
that flies it all.

## Projects

Each subsystem is its own repository with its own CI and versioned code.

| Repo | What it is | Stack |
|---|---|---|
| [indomitus-rover-core](https://github.com/UCUSpaceRobotics/indomitus-rover-core) | The ROS 2 stack that runs on the rover's onboard computer — navigation, control, dockerized prod/dev images published to GHCR. | ROS 2 Humble, Nav2, ros2_control, MoveIt, Docker |
| [indomitus-embedded-control](https://github.com/UCU-MarsRover/indomitus-embedded-control) | Firmware for every microcontroller on the rover (ESP32 / ESP32S3 / ESP32C3), one PlatformIO project per subsystem. | C++, C, PlatformIO |
| [indomitus-drone](https://github.com/UCUSpaceRobotics/indomitus-drone) | ROS 2 stack for the rover's onboard drone. | ROS 2, MATLAB |
| [indomitus-ground-station](https://github.com/UCUSpaceRobotics/indomitus-ground-station) | Ground station software — joystick control and serial communication with the rover over ESP32 links. | Docker, ESP32 |

<p align="center">
  <a href="https://www.instagram.com/indomitus.ucu/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"></a>
  <a href="https://www.facebook.com/people/Indomitus-Ucu/61588639040416"><img alt="Facebook" src="https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/ucu-space-robotics-1664a23b7/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=LinkedIn&logoColor=white"></a>
  <a href="https://www.tiktok.com/@ucu.space.robotics"><img alt="TikTok" src="https://img.shields.io/badge/TikTok-%23000000.svg?style=for-the-badge&logo=TikTok&logoColor=white"></a>
</p>
