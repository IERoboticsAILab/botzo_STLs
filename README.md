<div align="center">
<h1>BOTZO 🐾</h1>

**`The good boy quadruped robot :)`**

<p align="center">
    <a href="https://www.instagram.com/botzo.ie/" target="_blank" rel="noopener noreferrer">
        <img alt="Instagram" src="https://img.shields.io/badge/Instagram-%232C3454.svg?style=for-the-badge&logo=Instagram&logoColor=white" />
    </a>
    <a href="" target="_blank" rel="noopener noreferrer">
        <img alt="LinkedIn" src="https://img.shields.io/badge/Youtube-%232C3454.svg?style=for-the-badge&logo=Youtube&logoColor=white" />
    </a>
    <a href="mailto:botzoteam@gmail.com">
        <img alt="Gmail" src="https://img.shields.io/badge/Gmail-2c3454?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="">
        <img alt="Views" src="https://komarev.com/ghpvc/?username=botzo&color=blue&style=for-the-badge&abbreviated=true" />
    </a>

more about botzo [here](https://github.com/IERoboticsAILab/botzo)

![botzo](https://github.com/botzo-team/our_images_and_videos/blob/main/botzo_new_final_design.png)

</p>
</div>



# Design
here u can download the **STLs** for the robot, find the **list of components**, **price** and **assembly procedure**

_If you have Fusion360 licence you can download the .f3z and modify models as you like. Otherwise just download the stl file and you will be rady to 3D print your own Botzo_


### The Leg

The leg design was inspired by [Chop](https://hackaday.io/project/171456-diy-hobby-servos-quadruped-robot/details) from _Miguel Ayusto Parrilla_. With this design the leg weight is concentated in the shoulder, decreaseing the inertia when walking and so improve stability.

![leg](https://github.com/botzo-team/our_images_and_videos/blob/main/FULL_LEG.gif)


### The Body

For the body we make room for all components and cables, plus leaving space on the dorso to add Lidar and Webcams for future abilities.

![leg](https://github.com/botzo-team/our_images_and_videos/blob/main/animation_new_final_body.gif)

# Assembly the robot

<details>
  <summary><strong>Components List</strong></summary>


| Quantity | Component                        | Link         | Price (Single) | Component Total | Status       | Description                           | Measures (cm) |
|----------|----------------------------------|-------------|----------------|----------------|--------------|--------------------------------------|--------------|
| x1       | Arduino Mega                     | Amazon      | 25.99€         | 25.99€         | In the lab   | Control over servos and IMU         |              |
| x1       | Raspberry Pi                     | -           | -              | -              | In the lab   | Brain                                |              |
| x1       | Raspberry Pi camera module V2 8MP | Amazon      | 13.79€         | 13.79€         | In the lab   | Camera module for Raspberry         |              |
| x1       | Buck converter 5V-5A out         | Amazon      | 11.99€         | 11.99€         | In the lab   | Buck converter 5V-5A (25W) for Rpi  |              |
| x5       | Buck converter 5-40V 12A out     | Amazon      | 35.99€         | 35.99€         | In the lab   | Buck converters for servos          | 6x5x2        |
| x12      | Servo DS3225 25kg                | -           | -              | -              | In the lab   | Actuators for legs                  |              |
| x1       | MPU-6050                         | -           | -              | -              | In the lab   | Balancing sensor                    | 2x2.3x0.7    |
| x2       | LiPo batteries RC                | Amazon      | 45.99€         | 91.98€         | In the lab   | Power in series                     |              |
| x1       | Oled Display                     | Amazon      | 9.99€          | 9.99€          | In the lab   | Display informations                |              |
| x1       | PS3 controller                   | Amazon      | 17.99€         | 17.99€         | In the lab   | PS3 controller to move robot        |              |
|        |                    |       |         |        |   |       |              |
| x20      | 8x3x4 mm bearings                | Amazon (x2) | 7.09€          | 14.18€         | Need to buy  | Bearings for moving parts           |              |
| x4 | 10x5x4 mm bearings | | | | | For shoulder stronger axes| |
| x1       | Dean T Connectors                | Amazon      | 9.99€          | 9.99€          | In the lab   | Connection of the circuit           |              |
| x1       | Cables 14 AWG                    | Amazon      | 25.5€          | 25.5€          | In the lab   | Cables high current                 |              |
| x1       | Cables 10 AWG                    | Amazon      | 16.99€         | 16.99€         | Need to buy  | Cables high current                 |              |
| x1       | TPU Bambu filament               | Bambu       | 44.73€         | 44.73€         | Need to buy  | TPU for foot                        |              |
| | Set of M3, M2.5 and M2 screws| | | | | | |
| | Set of inserts for M3, M2.5 and M2 screws | | | | | | |

**Total: 256.39€**

_Price can vary depending on what you already have, but the goal is to stay  under 500€_

</details>

<br>
<br>

<details>
  <summary><strong>Circuit Diagram</strong></summary>

  ![circuit design](https://github.com/botzo-team/our_images_and_videos/blob/main/full_circuit_scketch.png)

</details>

<br>
<br>

<details>
  <summary><strong>Leg Assembly</strong></summary>

![leg](https://github.com/botzo-team/our_images_and_videos/blob/main/assemble_one_leg_timelapse.gif)

</details>

<br>
<br>

<details>
  <summary><strong>Body Assembly</strong></summary>

_commin soon_

</details>

<br>
<br>
<br>

# URDF

_deprecated_

To create URDF visit our repo [here](https://github.com/botzo-team/create_URDF).
You will use [body_urdf.f3d](https://github.com/botzo-team/STL_files/blob/main/URDF%20file/body_urdf.f3d) file to build your urdf, or just download ours [here](https://github.com/IERoboticsAILab/botzo_STLs/tree/main/URDF%20file)

leg:

![urdf](https://github.com/botzo-team/our_images_and_videos/blob/main/urdf_leg.png)

Body:

![urfd](https://github.com/botzo-team/our_images_and_videos/blob/main/urdf_body.png)