---
title: "MedXplore Competition"
excerpt: "Knee brace prototype--2nd place within division.<br>[![MedXplore](/images/MedXplore/exo.png)](/portfolio/medxplore/)"
collection: portfolio
permalink: /portfolio/medxplore/
---

[Github Repository](https://github.com/mckenzie-mccain/MedXplore)

**Summary:** Our team placed 2nd in the Muscular category, where we focused on a postoperative rehabilitation challenge: addressing quadriceps atrophy and impaired neuromuscular activation following lower-extremity knee injury and surgery. We explored how integrating surface EMG and NMES into a brace-mounted system could support clinician-directed rehabilitation by improving muscle re-education and tracking recovery over time.

**Team Members:** [Jack Bluethmann](https://www.linkedin.com/in/jack-bluethmann-735490291/), [Thomas Lopez](https://www.linkedin.com/in/thomas-lopez-7a353729b/), [Julia Sopala](https://www.linkedin.com/in/julia-sopala/), [Arshya Kamrani](https://www.linkedin.com/in/arshya-kamrani-ab8998330/), [Will Donaldson](https://www.linkedin.com/in/will-donaldson-b2a71a327/), and [Ryo Kato](https://www.linkedin.com/in/ryokato-texasam/).

## Technical Implementation

The exoskeleton knee brace was controlled using the [H.U.R.C. controller](https://mckenzie-mccain.github.io/portfolio/hurc/) paired with an ESP32-WROOM microcontroller programmed in embedded C++. The actuation system utilized three 20kg servos driven by two PCA9685 servo drivers in a three-planet planetary gear configuration, providing the torque necessary for controlled knee extension and flexion. A Myoware 2.0 muscle sensor was integrated to detect quadriceps activation and provide EMG feedback for muscle re-education tracking.

[Working Prototype Demonstration](/images/MedXplore/IMG_2136.mov)

The control interface mapped H.U.R.C. inputs to servo positions across a 270-degree range of motion:

* X button: full extension (0°/180°)
* A button: mid-range position (135°/45°)
* B button: full flexion (270°/90°)
* Right/left bumpers: continuous extension/flexion control
* Right/left triggers: speed adjustment (faster/slower)

|    ![Prototype](/images/MedXplore/irl-brace.HEIC)  |  ![MyoTronic](/images/MedXplore/group-pic.JPG) |
| :------------------------------------------------: | :--------------------------------------------: |
|               *Exoskeleton Prototype*              |         *Competition Team (MyoTronic)*         |

[View the Slides](https://www.canva.com/design/DAG_823u-uA/aoHYZcGOrUf4Sdd7kC89_A/edit?utm_content=DAG_823u-uA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


[← Back to Portfolio](/portfolio/)