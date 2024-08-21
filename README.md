# V1.0-Dexhand

<br>
<div align="center">

<img width=100px height=18px src="https://img.shields.io/badge/lenguage-c++-blue" alt="explode"></a>
<img width=100px height=18px src="https://img.shields.io/badge/status-In Progress-yellow" alt="explode"></a>
</div>

From my final grade project, [Programming drones with imitation learning and neural networks](https://github.com/RoboticsLabURJC/2023-tfg-adrian-madinabeitia), the idea arose to combine this concept with the field of prosthetics. The Dexhand model created by was found, which I found quite interesting for this project.

---
---

## Index

- [V1.0-Dexhand](#v10-dexhand)
  - [Index](#index)
  - [Original links](#original-links)
  - [3D printing](#3d-printing)
  - [Material list](#material-list)
  - [License](#license)

---
---

## Original links

* [Main page](https://www.dexhand.org/) -> Page where all the original project allocates.
  
* [Assembly playlist](https://www.youtube.com/playlist?list=PLy7gxZH9jzfQB2YJvAl5Y0FLJvxzb_83F) -> This is Rob Knight’s series of assembly videos.
  
* [Cad model](https://cad.onshape.com/documents/16c809d35214bd31c5b0324f/w/56b2fb82f7bdce505771766f/e/df78e66574dc7dbd45e4826c?renderMode=0&uiState=6358f3f91587a72417a28b1c) -> Model of the full arm.


GitHub repos:

  * [Models](https://github.com/TheRobotStudio/V1.0-Dexhand) -> All the STL files are here.
  
* [Mechanical build](https://github.com/iotdesignshop/dexhand-mechanical-build) ->  Instructions, and a build Wiki from IoT design.
  
* [Arduino firmware](https://github.com/iotdesignshop/dexhand-ble) -> Firmware for the Arduino Nano RP2040.
  
* [ROS2 implementation](https://github.com/iotdesignshop/dexhand_ros2_meta) -> ROS 2 drivers and demonstration packages.

---
---

## 3D printing

The original design was tested for high speed printing using a 0.6mm diameter nozzle and 0.4mm layer thickness except for the tendon spools which benefit from printing at 0.3mm layer thickness or better.

---
---

## Material list

- [ ] 16 slim micro-servos

* ES3301 (approx $6.6)
* ES3302 (approx $9.2)
* ES3351  (approx $8.5)
* ES3352 (approx $12)

- [ ] 2 standard micro servos for wrist flexion and extension.

* [Feetech SCS2332](https://feetechrc.com/product-name_55300.html)

- [ ] 1 standard servo needed for axial wrist rotation (optional)
Feetech [SCS15](https://feetechrc.com/6v-15kg-digital-robot-steering-gear.html) or any servo that fits inside the envelope 40*20*40.5mm.

- [ ] [2mm diameter steel pins](https://amzn.to/3VYrnfh)

- [ ] [M2 screw and washer kits](https://amzn.to/3sf4NkE)

- [ ] [M2 brass threaded inserts M2 * 4mm long * 3.5mm](https://amzn.to/3yYl1lY)

- [ ] [Kite or fishing line for finger tendons](https://amzn.to/3DgjNoF)

- [ ] [0.8mm kiteline](https://amzn.to/3GMKQJL) for the finger ligaments and wrist tendons.

- [ ] [Ball Bearings 6*10*3](https://amzn.to/3Dj7cBn) - Need 50 for a hand, packs of 10 available which are enough for the sample finger.

- [ ] [Ball Bearings 2*6*3 or 2*6*2.5](https://amzn.to/3yYlTHg) - Need 6 for the wrist

- [ ] [Ball Bearings 15*21*4](https://amzn.to/3TsMSTO) - Need 4 for the wrist

- [ ] [Ball Bearings 3*8*4](https://amzn.to/3VyE28O) - Need 6 for the wrist

- [ ] [M3 * 70mm caphead](https://amzn.to/3HM0Rjx) bolt (grade 12.9 ideally)
Need 2 (1 is cut down to 60mm)

---
---

## License

Follow the author of the project @therobotstudio
Get involved at patreon.com/therobotstudio

<div align="center">

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

</div>

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
