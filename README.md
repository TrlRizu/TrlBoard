<h1 align="center">TRL BOARD</h1>
<h3 align="center">ESP32-S3-WROOM-1 Devboard • IMU + Battery Support</h3>

--- 

## Features
 - ESP-32-S3-WROOM-1
 - MPU-6050 IMU sensor
 - BQ24072RGT Battery Charger 
 - B2B-XH-A_LF__SN_ Connector
 - TPS63060 Buck Boost Converter
 - CH340C USB-UART bridge
 - USB-C connection
 - 1x20 x2 Connector pins (GPIO/GND/5V/3V3)

---

## PCB Schematic & Layout
#### See full [TrlBoard-schematic](TrlBoard-schematic.pdf).

The schematic: 

![](images/schematic.png)


Front: 
![](images/front.png)

Back: 
![](images/back.png)

---

## Renders

![](images/front-pcb.png)

![](images/back-pcb.png)

![](images/ortho.png)

---

## Bill Of Materials

The board is manufactured through JLCPCB's PCBA though not complete as the ESP32-S3-WROOM-1 and header pins are going to be hand-soldered.

> For the cost of the board's individual components check [Components](TrlBoard-Componnents.csv).

> For my case (PCBA + ESP32 + Connector pins) check [BOM](TrlBoard-Bom.csv)

| Designator      | Footprint                        | Quantity | Quantity/Board | Value                 | Link                                                                                                                                                                                                                                    | Cost  | Running Cost |
|-----------------|---------------------------------|----------|----------------|----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|--------------|
| PCBA            |                                 | 2        |                |                      | JLCPCB                                                                                                                                                                                                                                 | 72.19 | 72.19        |
| U2              | ESP32-S3-WROOM-1                | 2        | 1              | ESP32-S3-WROOM-1     | [AliExpress](https://www.aliexpress.com/item/1005008405001510.html?spm=a2g0o.cart.0.0.186438daN5XPTv&mp=1)                                                                                                                        | 11.58 | 83.77        |
| J2, J4          | PinHeader_1x22_P2.54mm_Vertical | 4        | 2              | Conn_01x12           | [AliExpress](https://www.aliexpress.com/item/4000988113226.html?spm=a2g0o.productlist.main.22.78fc5d654BIxDA&algo_pvid=1fd1bedd-4f7d-422c-8738-7bcee1d384c0&pdp_ext_f=%7B%22order%22%3A%221942%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000988113226%7C_p_origin_prod%3A) | 1.6   | 85.37        |
|                 |                                 |          |                | Conn_01x10           | [AliExpress](https://www.aliexpress.com/item/4000988113226.html?spm=a2g0o.productlist.main.22.78fc5d654BIxDA&algo_pvid=1fd1bedd-4f7d-422c-8738-7bcee1d384c0&pdp_ext_f=%7B%22order%22%3A%221942%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000988113226%7C_p_origin_prod%3A) | 1.5   | 86.87        |
| AliExpress Tax  |                                 |          |                |                      |                                                                                       | 1.47  | 88.34        |
|                 |                                 |          |                | **Total Cost**       |                                                                                       |       | **88.34**    |




---

## Intended purpose

TRL-Board is a flexible devboard aimed to power personal robotic prototypes, with ideas such as: 
- Quadrupped Bot
- Line-follower 
- Robotic Arm Mirrored control

Ideas to follow!

--- 


