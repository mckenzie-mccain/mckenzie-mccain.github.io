---
title: "Hatchling Robot"
excerpt: "Competition robot--achieved highest stack record.<br>[![Hatchling](/images/Hatchling/tara.jpeg)](/portfolio/hatchling/)"
collection: portfolio
permalink: /portfolio/hatchling/
---

[Github Repository](https://github.com/mckenzie-mccain/Personal_Robot-Tara)

**Summary:** In Spring 2025, I designed a robot from scratch for the TURTLE Robotics Hatchling competition, Turtle Towers, where my team placed 2nd out of 21 teams. The challenge required retrieving 2.5-inch building blocks from a central cube location and transporting them back to the team zone within a 2:30 match, competing head-to-head against an opposing team.

**Team Members:** [Alex Runyan](https://www.linkedin.com/in/alexander-runyan-9a2bbb348/) and [Drew Wheaton](https://www.linkedin.com/in/drew-wheaton/).

## Technical Implementation

The robot integrated an ESP32-WROOM microcontroller with an L298N motor driver to control TT motors for both drivetrain locomotion and the telescoping arm mechanism. I programmed PWM motor control and mechanism functions using embedded C++, implementing the [TurtleReceiver library](/files/Fall%202025%20HURC%20Docs.pdf) to interface with the wireless [H.U.R.C. controller](https://mckenzie-mccain.github.io/portfolio/hurc/).

The primary collection mechanism utilized a [telescoping arm](https://www.youtube.com/watch?v=gPZPs-l5LiU) driven by two DC motors for vertical extension and an SG90 micro servo to actuate the claw. This design allowed for optimized stacking speed, giving the robot the title of being a record holder.

<!-- mention differential drive? updated github code with most recent iteration (tara??) -->

|           ![New Record](/images/Hatchling/record-crop.jpeg)      |  ![Turtle Towers Competition Layout](/images/Hatchling/turtle-towers.png) |
| :--------------------------------------------------------------: | :-----------------------------------------------------------------------: |
|        *Competition Robot Reaching Highest Stack Score (5)*      |                      *Turtle Towers Competition Layout*                   |

[← Back to Portfolio](/portfolio/)