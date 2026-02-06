---
title: "H.U.R.C."
excerpt: "Universal controller for competition robots.<br>[![HURC](/images/Hatchling/hurc.JPG)](/portfolio/hurc/)"
collection: portfolio
permalink: /portfolio/hurc/
---

[Github Repository](https://github.com/turtle-robotics/HURC_dev2)

H.U.R.C. (Hatchling Universal Robot Controller) is the controller used for hatchling competitions through the [TURTLE robotics development program](https://www.turtlerobotics.org/development-programs). In Fall 2025, I designed and built seven controllers to support a growing number of teams. 

The controller uses ESP-NOW peer-to-peer communication over Wi-Fi, pairing directly to robots using each ESP32's MAC address, supporting up to 20 paired peers. The interface follows an Xbox-style layout including:
* x2 triggers, x2 bumpers, x2 joysticks
* XYAB buttons, menu, and dpad

For ease of use, a software library ([TurtleReciver](/files/Fall%202025%20HURC%20Docs.pdf)) was made to map each button/trigger input into simple, reusable functions. This simplifies the software process, especially for newer members.

Unlike a standard Xbox controller, H.U.R.C. implements an OLED display to provide direct feedback for debugging and displaying button/trigger controls.The  figures below show the circuit diagram I made to optimize the assembly and the iterative production process.

|    ![Circuit Diagram](/images/Hatchling/circuit-diagram.png)     |  ![Iterative Production](/images/Hatchling/hurc_production.JPG)  |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|        *HURC V2 Circuit Diagram created in LucidSpark*           |          *Iterative Production Process of Controllers*           |


[← Back to Portfolio](/portfolio/)