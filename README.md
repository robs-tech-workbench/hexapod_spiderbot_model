# Spiderbot STLs: 3D-Printed Hexapod Spider Robot Build Guide

## Table of Contents

- [Spiderbot STLs: 3D-Printed Hexapod Spider Robot Build Guide](#spiderbot-stls-3d-printed-hexapod-spider-robot-build-guide)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Acknowledgments](#acknowledgments)
  - [Disclaimer](#disclaimer)
  - [Pre-requisites](#pre-requisites)
  - [Installation](#installation)
  - [Components](#components)
    - [Body Parts](#body-parts)
    - [Leg Parts](#leg-parts)
    - [Other Parts](#other-parts)
  - [Contribution](#contribution)
  - [License](#license)

---

## Introduction

This repository contains STL files, 3D printing instructions, and build documentation for SpiderBot, a 3D-printed spider robot. Here you'll find all you need to build your own SpiderBot, whether you're a beginner or an experienced robotics enthusiast.

---
## Acknowledgments

While the [MakeYourPet project](https://github.com/makeyourpet/hexapod) served as an initial inspiration, the 3D parts used in this Hexapod Spiderbot Model are not from their official designs. Special credit goes to 'amelendez8', a Discord server user from MakeYourPet's community. I have adapted and modified his design for the purpose of this project. You can find his original work [here](https://github.com/almelnz2005/hexapod).

---
## Disclaimer

This project is intended for educational purposes. Please exercise caution and read all safety guidelines when working with electronics and 3D printers. We are not responsible for any damage caused during the build.

---

## Pre-requisites

- 3D printer with PLA filament
- Basic knowledge of electronics
- Soldering kit
- [Optional] CAD software like Fusion 360 for customization

---

## Installation

Clone this repository using the following command:

```bash
git clone https://github.com/YourUsername/ArachnoBot-STL.git
```

---

## Components

### Body Parts

| Part Name | Description | Count |3D Printing Instructions | Photo | Link to STL |
|-----------|----------|--------|--------------------------|-------|-------------|
| Frame | This serves as the robot's central structure | x1 | ![Alt text](media/frame.png) | |
| Carapace | Consisits of 3 parts: Front, Mid, Back. <br />**TODO:** tongue and groove technique | Layer height: 0.2mm, Fill: 20%, Supports: Yes | ![Main Body](media/new_carapace.png) | [Download STL](./STL/MainBody.stl) |
| Power compartment | Holds the 2S LiPo Battery | Layer height: 0.2mm, Fill: 30% | ![Alt text](media/power_compartment.png)| [Download STL](./STL/BatteryHolder.stl) |
| Power compartment door | **TODO:** Needs improvement - maybe rewoork it to be snap-fit design || ![ sssss](media/power_door.png)|
| Electronics plate | plate between Pawer compartment Frame | | ![Alt text](media/electronics_plate.png) |
| Controller plate | Allows to attach controller (Compatible with raspberry and Serco 2040) to Electronics plate or Carapace (middle) | | ![Alt text](media/controller_plate.png) |

### Leg Parts

| Part Name | Comments | 3D Printing Instructions | Photo | Link to STL |
|-----------|----------|--------------------------|-------|-------------|
|Servo joint|||![Alt text](media/servo_joint.png)|
|Leg rib||| ![Alt text](media/leg_rib.png) |
| Coxa Side 1 | Upper leg part | Layer height: 0.2mm, Fill: 30% | ![Alt text](media/coxa_1.png) | [Download STL](./STL/Femur.stl) |
| Coxa Side 2 | Upper leg part | Layer height: 0.2mm, Fill: 30% | ![Alt text](media/coxa_2.png) | [Download STL](./STL/Femur.stl) |
| Femur side 1 | | | ![Alt text](media/femur_1.png) |
| Femur side 2 | | | ![Alt text](media/femur2.png) |
| Tibia top | Lower leg part | Layer height: 0.1mm, Fill: 30% | ![Alt text](media/tibia_top.png)| [Download STL](./STL/Tibia.stl) |
| Tibia bottom | | | ![Alt text](media/tibia_bottom.png) |
| Leg shield ||| ![Alt text](media/leg_shield.png) |
| Micro switch holder ||| ![Alt text](media/switch_holder.png) |
| Micro switch cover | | | ![Alt text](media/switch_cover.png) |
| Leg tip | | | ![Alt text](media/leg_tip.png) |
| Claw | Made out of soft material it silences robot movement and improves its traction to the ground | Material: TPU | ![Alt text](media/claw.png) |
### Other Parts

| Part Name | Comments | 3D Printing Instructions | Photo | Link to STL |
|-----------|----------|--------------------------|-------|-------------|
| Spiderbot stand | Consists of 2 parts that can be glued together: stand and leg. Allows for robot testing in the air. LEg should be attache dto something stable (tripod, weights etc) | Layer height: 0.3mm, Fill: 40% Scale leg in Z direction of you need it higher. | ![Alt text](media/stand.png)  | [Leg](./STL/ServoMount.stl)<br />------<br /> [Stand](./STL/ServoMount.stl) |

---

## Contribution

Contributions are welcome! Please read the [Contribution Guidelines](CONTRIBUTING.md) for more information.

---

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
