::: {align="center"}

STM32 MPU6050 PCB Design

Custom Embedded Hardware Design using Altium Designer

<img src="https://img.shields.io/badge/Altium%20Designer-PCB%20Design-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white"/>{=html}
<img src="https://img.shields.io/badge/STM32-Microcontroller-03234B?style=for-the-badge"/>{=html}
<img src="https://img.shields.io/badge/MPU6050-6--Axis%20IMU-00897B?style=for-the-badge"/>{=html}
<img src="https://img.shields.io/badge/PCB-4%20Layer-1565C0?style=for-the-badge"/>{=html}
:::

Project Overview

This project involves the design and development of a custom four-layer
PCB integrating an STM32 microcontroller with an MPU6050 six-axis motion
sensor.

The PCB is designed using Altium Designer, focusing on component
integration, signal routing, power distribution, grounding architecture
and compact PCB layout.

The MPU6050 combines a three-axis accelerometer and a three-axis
gyroscope, enabling motion sensing and orientation measurement
applications.

3D PCB Visualization

::: {align="center"}
<img src="images/3d.png" width="85%" alt="3D PCB View"/>{=html}

PCB 3D View

<img src="images/3d_image.png" width="85%" alt="3D PCB Render"/>{=html}

PCB 3D Render
:::

PCB Layout

::: {align="center"}
<img src="images/pcb_layout.png" width="95%" alt="PCB Layout"/>{=html}

Four-Layer PCB Layout
:::

Circuit Schematic

::: {align="center"}
<img src="images/pcb_schematic.png" width="95%" alt="Circuit Schematic"/>{=html}

STM32 MPU6050 Circuit Schematic
:::

Hardware Specifications

Parameter          Specification

Microcontroller    STM32
Motion Sensor      MPU6050
Sensor Interface   I2C
Accelerometer      3-Axis
Gyroscope          3-Axis
PCB Architecture   4-Layer
Design Software    Altium Designer

PCB Layer Stackup

Layer   Configuration

L1      Top Signal Layer
L2      Ground Plane
L3      Ground Plane
L4      Bottom Signal Layer

The multilayer architecture provides dedicated internal ground reference
layers and separate signal routing layers.

Key Design Features

STM32 microcontroller integration.

MPU6050 six-axis motion sensor integration.

I2C-based sensor communication.

Four-layer PCB architecture.

Dedicated internal ground layers.

Component placement and signal routing.

Custom connector and interface arrangement.

3D PCB modelling and visualization.

Design Tools

::: {align="center"}
<img src="https://img.shields.io/badge/Altium%20Designer-PCB%20Design-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white"/>{=html}
<img src="https://img.shields.io/badge/STM32-Embedded%20Controller-03234B?style=flat-square"/>{=html}
<img src="https://img.shields.io/badge/MPU6050-Motion%20Sensing-00897B?style=flat-square"/>{=html}
:::

Repository Structure

stm32_mpu6050_pcb/
│
├── images/
│   ├── 3d.png
│   ├── 3d_image.png
│   ├── pcb_layout.png
│   └── pcb_schematic.png
│
├── Components - 01.11.26 - 12.54/
│
├── AltiumSTM32_PCB.PrjPcb
├── AltiumSTM32_PCB.PcbDoc
├── AltiumSTM32_Schematic.SchDoc
├── .gitignore
└── README.md

Potential Applications

Motion tracking systems.

Orientation and tilt measurement.

Inertial measurement applications.

Robotics and embedded control systems.

Sensor-based electronic applications.

Author

Ratnakar Sahoo

Electronics and Telecommunication Engineering
Veer Surendra Sai University of Technology (VSSUT), Odisha

GitHub Profile

Project
Repository

::: {align="center"}
STM32 | MPU6050 | Embedded Hardware | PCB Design

Designed using Altium Designer.
:::
