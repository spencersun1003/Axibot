# Axibot: A Multifunctional Robot with High Precision Arm.

## Introduction

This is a work during the intern in State Key Laboratory of Intelligent Control and Decision of Complex Systems.
The work placed 4nd place in Geekpwn 2018 International Cybersecurity and AI Contest, and won 2nd prize in the Science and Technology Works Competition of Beijing Institute of Technology.

We establish the core control system through Arudino microcontroller, and the video transmission system through Raspberry Pi. Modifying the CoreXY structure commonly used in 3d printers, we realize the three-dimensional high-precision movement of the robot arm with the screw and other structures. We further innovatively propose an end structure to achieve the switching of the actuator. A unified power supply system is also designed based on the voltage conversion module.

At the software level, we implement the high-sensitivity wireless control through the optimization algorithm, stabilizing the chassis movement through the closed-loop PID speed regulation mechanism. A real-time video transmission system is also established.




 <img src="./Demo/Overall1.jpg" width = "200" align=center /> <img src="./Demo/Overall2.jpg" width = "200" align=center /> <img src="./Demo/Overall3.jpg" width = "200" align=center />

## Implementation

<table>
    <tr>
        <td>Module</td>
        <td>Quantity</td>
    </tr>
    <tr>
        <td>Arduino Mega 2560</td>
        <td>2</td>
    </tr>
        <tr>
        <td>Raspberry Pi Zero W</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Step Motor (A4988 Enabled)</td>
        <td>5</td>
    </tr>
        <tr>
        <td>Servo</td>
        <td>2</td>
    </tr>
    <tr>
        <td>DC motor (L298N Enabled)</td>
        <td>4</td>
    </tr>
    <tr>
        <td>Main Camera</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Secondary Camera</td>
        <td>1</td>
    </tr>
    <tr>
        <td>2.4G contorller</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Regulator Module</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Others</td>
        <td>Li-ion Battery (&Meter)</td>
    </tr>
</table>




## Teamwork

Yue Sun: Hardware & Software Development, machine design

Shuo Wang: Hardware Development, machine design

Yufeng Wu: Hardware Development

Date: 10/27/2018

