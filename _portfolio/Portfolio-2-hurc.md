---
title: "H.U.R.C."
excerpt: "Universal controller for competition robots.<br>[![HURC](/images/Hatchling/hurc.JPG)](/portfolio/hurc/)"
collection: portfolio
permalink: /portfolio/hurc/
---

[Github Repository](https://github.com/turtle-robotics/HURC_dev2)

H.U.R.C. also known as the Hatchling Universal Robot Controller, is the controller that is used for hatchling competitions through the [TURTLE robotics development program](https://www.turtlerobotics.org/development-programs). In Fall 2025, I designed and built 7 controllers to supply to the increased number of teams competing. 

Currently, the controller utilizes ESP-NOW P2P connection across wifi using MAC addresses and can support up to 20 users. The controller follows an xbox layout with the following controls:
    * x2 triggers, x2 bumpers, x2 joysticks
    * XYAB buttons, menu, and dpad

For ease of use, a library ([TurtleReciver](/files/Fall%202025%20HURC%20Docs.pdf)) was made to create custom controller functions to call each trigger/button input to simplify the software process for competing teams. 

Unlike an xbox controller, an OLED display is implemented to show button control feedback on the screen for debugging. The two figures below show the circuit diagram I made to optimize the production efficiency and the iterative process of production.

|    ![Circuit Diagram](/images/Hatchling/circuit-diagram.png)     |  ![Iterative Production](/images/Hatchling/hurc_production.JPG)  |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|        *HURC V2 Circuit Diagram created in LucidSpark*           |          *Iterative Production Process of Controllers*           |


[← Back to Portfolio](/portfolio/)