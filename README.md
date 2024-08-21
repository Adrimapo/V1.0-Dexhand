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


**GitHub repos:**

* [Models](https://github.com/TheRobotStudio/V1.0-Dexhand) -> All the STL files are here.
  
* [Mechanical build](https://github.com/iotdesignshop/dexhand-mechanical-build) ->  Instructions, and a build Wiki from IoT design.
  
* [Arduino firmware](https://github.com/iotdesignshop/dexhand-ble) -> Firmware for the Arduino Nano RP2040.
  
* [ROS2 implementation](https://github.com/iotdesignshop/dexhand_ros2_meta) -> ROS 2 drivers and demonstration packages.

---
---

## 3D printing

The original design was tested for high speed printing using a 0.6mm diameter nozzle and 0.4mm layer thickness except for the tendon spools which benefit from printing at 0.3mm layer thickness or better.

In our case, the hand will be printed with a Neptune 4.0 printer with the next parameters:

* **Nozzle diameter:** 0.4
* **Line width:** 0.4
* **Layer height:** 0.25
* **Infill density:** 15%


---
---

## Material list

| Item | Original price | Cheep price | Quantity | Description |
|------|--------------|------------------|-----------------|-------------|
| ES3352  | [11.69€](https://www.amazon.com/-/es/GoGoRc-EMAX-ES3352-engranaje-0-44/dp/B07ZQGFRVF/ref=sr_1_2?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&sr=8-2) | [4.69€](https://es.aliexpress.com/item/1005006064458628.html?spm=a2g0o.productlist.main.9.d466s4w2s4w2fE&algo_pvid=b5651313-dcdd-46ce-81eb-be881169888a&utparam-url=scene%3Asearch%7Cquery_from%3A) | 16 | - |
| 2 standard micro servos | N/A | [0.99€](https://es.aliexpress.com/item/1005006707818210.html?spm=a2g0o.productlist.main.9.6f6f2007p0HoXP&algo_pvid=0d9ff2bc-2cbf-4a64-a255-ed3b39d9da01&utparam-url=scene%3Asearch%7Cquery_from%3A) | 2 | Wrist flexion and extension |
| 1 standard servo | N/A | [1.65€](https://es.aliexpress.com/item/1005005959332828.html?spm=a2g0o.productlist.main.65.93b83cf1gywzHB&algo_pvid=164e0617-077d-457f-afea-146e3c801a69&utparam-url=scene%3Asearch%7Cquery_from%3A) | 1 | Faxial wrist rotation |
| 2mm diameter steel pins | [11€](https://amzn.to/3VYrnfh) | [1.38€](https://es.aliexpress.com/item/32991861162.html?spm=a2g0o.productlist.main.1.723emQmhmQmhtj&algo_pvid=eead8448-4271-4f40-a023-f4faaee4b2f7&utparam-url=scene%3Asearch%7Cquery_from%3A) | Varies | - |
| M2 screw and washer kits | [10.78€](https://amzn.to/3sf4NkE) | N/A | N/A | - |
| M2 brass threaded inserts M2 * 4mm long * 3.5mm | [10€](https://amzn.to/3yYl1lY) | [0.99€](https://es.aliexpress.com/item/1005005776999972.html?spm=a2g0o.productlist.main.13.1525fCSAfCSAIr&algo_pvid=bb2bb8f0-db5b-408c-891f-e724fd415c47&utparam-url=scene%3Asearch%7Cquery_from%3A) | Varies | - |
| Kite or fishing line for finger tendons | [15.27€](https://amzn.to/3DgjNoF) | N/A | N/A | - |
| 0.8mm kiteline | [8.94€](https://amzn.to/3GMKQJL) | N/A | N/A | Finger ligaments and wrist tendons |
| Ball Bearings 6*10*3 | [10.32€ (pack of 10)](https://amzn.to/3Dj7cBn) | [0.99€ (per 10)](https://es.aliexpress.com/item/32962032067.html?spm=a2g0o.productlist.main.7.977827d16Dqpuu&algo_pvid=e8722c55-0139-4f9c-9b3c-edc9cca1827c&aem_p4p_detail=20240821073552901300786216560009336899&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=20240821073552901300786216560009336899_1) | 50 | 10 x finger |
| Ball Bearings 2*6*3 or 2*6*2.5 | [10.12€](https://amzn.to/3yYlTHg) | [0.99€](https://es.aliexpress.com/item/32962032067.html?spm=a2g0o.productlist.main.7.977827d16Dqpuu&algo_pvid=e8722c55-0139-4f9c-9b3c-edc9cca1827c&aem_p4p_detail=20240821073552901300786216560009336899&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=20240821073552901300786216560009336899_1) | 6 | Wrist |
| Ball Bearings 15*21*4 | [8.12€](https://amzn.to/3TsMSTO) | [3.86€](https://es.aliexpress.com/item/1005006498770883.html?spm=a2g0o.productlist.main.25.19e02eab7GNcPV&algo_pvid=71a624df-16ff-4b3a-bc54-7c084dc90ff6&utparam-url=scene%3Asearch%7Cquery_from%3A) | 4 | Wrist |
| Ball Bearings 3*8*4 | [7.18€](https://amzn.to/3VyE28O) | [0.99€](https://es.aliexpress.com/item/32962032067.html?spm=a2g0o.productlist.main.7.977827d16Dqpuu&algo_pvid=e8722c55-0139-4f9c-9b3c-edc9cca1827c&aem_p4p_detail=20240821073552901300786216560009336899&utparam-url=scene%3Asearch%7Cquery_from%3A&search_p4p_id=20240821073552901300786216560009336899_1) | 6 | Wrist |
| M3 * 70mm caphead | [4€](https://amzn.to/3HM0Rjx) | N/A | 2 | Wrist |
| **Total Price** | **302.27€** | **105.94€** | - |





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
