# Deposimeter

![](https://hackmd.io/_uploads/HJ_goqhU2.png)

## Materials

| Qty |  Description    |     Price      |           Link           | 
|-----|-----------------|----------------|--------------------------|
| 4 | Bearings Ø int. 8mm, Ø ext. 22mm ![](https://hackmd.io/_uploads/Hkcf4RBL2.jpg)| 2,37 € | [https://docs.rs-online.com/bb7b/A700000007851252.pdf](https://docs.rs-online.com/bb7b/A700000007851252.pdf) |
| 4 | Rodamientos de Cojinetes con Soporte Base de Cojinete de Zinc ![](https://hackmd.io/_uploads/rk-DNCSIh.jpg)| 17,12€| https://www.amazon.es/gp/product/B09MM15HLM/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1 |
|   | Steel profiles and bars | 115 € | Local shop "Ferros Blanch" |
|   | Galvanized metal sheet | 130 € | Local shop "Ferros Blanch" |

![](https://hackmd.io/_uploads/HJHnygU8h.png)

![](https://hackmd.io/_uploads/Bk5Poy8U2.png)

![](https://hackmd.io/_uploads/B1jvs1LU2.png)

![](https://hackmd.io/_uploads/rymGqq3Ih.png)

![](https://hackmd.io/_uploads/HJcDo1ULh.png)

## Electronics

| Qty | Description|Link|
|-----|------------|----|
|1| Rain Gauge Model RG-11 ![](https://hackmd.io/_uploads/SkQeZhNIh.jpg)| [https://rainsensors.com/wp-content/uploads/sites/3/2021/04/rg-11_instructions.pdf](https://rainsensors.com/wp-content/uploads/sites/3/2021/04/rg-11_instructions.pdf) |
|2| limit switch  **IP65** ![](https://hackmd.io/_uploads/Hyhie2EL3.jpg) | https://es.rs-online.com/web/p/interruptores-final-de-carrera/1258460 |
|1| Electric Linear Actuator **IP54** ![](https://hackmd.io/_uploads/Sk2DB3E82.jpg)| [https://docs.rs-online.com/77a5/A700000007396897.pdf](https://docs.rs-online.com/77a5/A700000007396897.pdf) |
|2|Pushbutton Switch ![](https://hackmd.io/_uploads/S1zSUhVL2.jpg)|https://www.mouser.es/datasheet/2/97/GPB527X2SERIES-474534.pdf|
|1|Adafruit Feather M0 Basic Proto ![](https://raw.githubusercontent.com/adafruit/Adafruit-Feather-M0-Basic-Proto-PCB/master/assets/image.jpg)|https://cdn-learn.adafruit.com/downloads/pdf/adafruit-feather-m0-basic-proto.pdf|
|1|Dual MC33926 Motor Driver Carrier![](https://a.pololu-files.com/picture/0J1889.350.jpg?6ba0515ca0eb26139cc0d7dd2dbc23d1)|https://www.pololu.com/product/1213|
|1|MP1584 Mini Step-Down Module ![](https://protosupplies.com/wp-content/uploads/2019/05/MP1584-Mini-Adjustable-DC-DC-Step-Down-Module.jpg)| https://protosupplies.com/product/mp1584-mini-adjustable-dc-dc-step-down-module/|


## Instructions

### **Machine Startup:**

1. Upon starting the machine, the rain sensor must be checked. If it is not detecting rain, the machine will move to the home position and initiate the automatic mode.
2. The home position is defined as the lid being positioned on top of the wet bucket.
![](https://hackmd.io/_uploads/SJjY9FQ83.jpg)

### **Loss of Power:**

1. In the event of a power loss while it is raining, the machine will restart.
2. Upon restart, the rain sensor will be read, and if rain is detected, the machine will verify if it is in the correct position by checking the appropriate endstop.
3. If the machine is not in the correct position, it will adjust its position accordingly.

### **Machine Control:**

1. The machine has a "manual mode" for controlling the lid movement.
2. To activate manual mode, press both buttons simultaneously. The LEDs inside the buttons will illuminate to indicate that manual mode is active.
![](https://hackmd.io/_uploads/Hk5o0FXLn.jpg)
3. In manual mode, the lid can be controlled using the buttons. Press and hold the green button to move the lid over the dry bucket, and press and hold the blue button to move the lid over the wet bucket.
4. During manual mode, the rain sensor will not be read, and the lid will not move if the rain sensor is triggered.
5. To exit manual mode and return to automatic mode, press both buttons simultaneously until the LEDs turn off.
![](https://hackmd.io/_uploads/BJiLg3ELn.jpg)
6. If the machine remains in manual mode for more than 30 minutes without any button presses, it will automatically switch back to automatic mode.

### **Bucket Handling:**

1. When the rain has stopped, the user should enter manual mode to release the buckets and position the lid for removing and replacing the buckets.
![](https://hackmd.io/_uploads/H1h-Jq7L3.jpg)
2. Before changing the buckets, it is important to **turn off the machine for safety reasons.** Once the buckets are replaced, the machine must be turned on again.
3. Upon machine restart, the sensor will be read, and the lid will move to the starting point.
4. It is crucial to reset the machine every time the lid is moved manually or ensure that the lid is in the desired position before leaving the machine unattended.

### **Resetting the Rain Sensor:**

![](https://hackmd.io/_uploads/H1xQJ9m8h.jpg)
1. To reset the rain sensor, use the switch located on top of the control box.
2. This action will restart the machine and reset the rain sensor.
