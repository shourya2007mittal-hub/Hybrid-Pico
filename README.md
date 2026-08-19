# Hybrid-Pico

<img width="491" height="607" alt="Screenshot 2026-08-17 012307" src="https://github.com/user-attachments/assets/24feae4e-2ba0-4e4f-a202-cbabcf93e3c9" />


So I have designed an RP2040 based Devboard with identical dimensions and pin layout as a A Raspberry Pi Pico . 
The board contains the same pin layout and dimensions the RP Pico .
These is a Boot pin for reboot and few onboard LEDS and 3.3V Voltage regulator for power supply to the micro-controllers. 
and my design has an upgrade . The Dev-board also includes an inbuilt IMU and Barometer . This broadens the scope of use for this board . As it could be easily connected  to a breadboard and the inbuilt IMU/Barometer sensors helps a lot in during  prototyping a project like a handheld with Gyro , a movement sensor device or  as a  compass or as a flight controller




## Features

- Based on RP-2040 Chip
- Identical Dimension and pin layout as RP-PICO
- 40 physical pins + 3 debugs pin and the board is breadboard compatible 
- Has inbuilt 3.3V  Voltage regulator
- has Inbuilt IMU (MPU-5060) and Barometer (BMP280)


  # Project Bill of Materials (BOM) & Cost Breakdown

This repository contains the hardware components, PCB fabrication, and assembly service details for the project.

---

## 🛠️ Bill of Materials (Components)

| Component / Comment | Quantity | Price (USD) | JLCPCB Part Link |
| :--- | :---: | :---: | :--- |
| **1uF** | 20 | $0.61 | [GRM033R61A105ME44D](https://jlcpcb.com/partdetail/MurataElectronics-GRM033R61A105ME44D/C76935) |
| **10uF** | 20 | $0.59 | [CL10A106MQ8NNNC](https://jlcpcb.com/partdetail/2043-CL10A106MQ8NNNC/C1691) |
| **10uF** | 20 | $0.59 | [CL10A106MQ8NNNC](https://jlcpcb.com/partdetail/2043-CL10A106MQ8NNNC/C1691) |
| **33pF** | 20 | $0.11 | [GRM0335C1H330JA01D](https://jlcpcb.com/partdetail/MurataElectronics-GRM0335C1H330JA01D/C76925) |
| **0.1uF** | 26 | $0.15 | [0201X104K100NT](https://jlcpcb.com/partdetail/270391-0201X104K100NT/C284966) |
| **27 ohm** | 4 | $0.15 | [0201X104K100NT](https://jlcpcb.com/partdetail/25843-0402WGF270JTCE/C25100) |
| **100nF** | 20 | $0.15 | [GRM033R61A104KE15D](https://jlcpcb.com/partdetail/MurataElectronics-GRM033R61A104KE15D/C76934) |
| **LED** | 6 | $0.68 | [XL0201SURC](https://jlcpcb.com/partdetail/XINGLIGHT-XL0201SURC/C3646923) |
| **USB_C_Receptacle_USB2.0_16P** | 2 | $4.08 | [USB31_TYPE_CFSABC](https://jlcpcb.com/partdetail/GSwitch-GT_USB7010ASV/C2988369) |
| **33R** | 20 | $0.06 | [0201WMJ0330TEE](https://jlcpcb.com/partdetail/416306-0201WMJ0330TEE/C423356) |
| **50K** | 6 | $0.76 | [GL3549](https://jlcpcb.com/partdetail/10622-GL3549/C10083) |
| **1K** | 22 | $0.06 | [0201WMF1001TEE](https://jlcpcb.com/partdetail/259895-0201WMF1001TEE/C270365) |
| **SW_Push** | 4 | $1.86 | [K5_1672SN01](https://jlcpcb.com/partdetail/Korean_HropartsElec-K5_1672SN01/C502360) |
| **MCP1700x-330xxTT** | 2 | $1.03 | [MCP1700_3002ETO](https://jlcpcb.com/partdetail/MicrochipTech-MCP1700T_3302ETT/C39051) |
| **MPU-6050** | 2 | $26.80 | [MPU6050](https://jlcpcb.com/partdetail/TDKInvenSense-MPU6050/C24112) |
| **BMP280** | 2 | $25.58 | [BMP280](https://jlcpcb.com/partdetail/BoschSensortec-BMP280/C83291) |
| **12MHz** | 5 | $1.27 | [NX3225GA_12MHZ](https://jlcpcb.com/partdetail/NDK-NX3225GA_12MHZ_STD_CRG2/C481407) |
| **RP2040** | 0 | $2.47 | [RP2040](https://jlcpcb.com/partdetail/RaspberryPi-RP2040/C2961140) |
| **W25Q16JVUXIQTR** | 2 | $0.987 | [W25Q16JVUXIQTR](https://jlcpcb.com/partdetail/WinbondElec-W25Q16JVUXIQTR/C5333738) |

---

## ⚙️ Fabrication & Assembly Fees

| Service Description | Quantity | Price (USD) |
| :--- | :---: | :---: |
| PCB Fabrication (5 pcs) | 1 | $4.00 |
| PCBA Setup Fee | 1 | $25.56 |
| PCBA Stencil Fee | 1 | $8.21 |
| Feeders Loading Fee | 1 | $19.89 |
| SMT Assembly Fee | 1 | $0.76 |
| Hand-soldering Labor Fee | 1 | $3.58 |
| Manual Assembly Fee | 1 | $0.64 |
| PCB Assembly Fixture | 1 | $16.42 |
| Special Components Fee | 1 | $0.06 |
| Packaging Fee | 1 | $0.49 |
| Shipping Fee | 1 | $11.68 |

---

## 💰 Total Cost

- **Grand Total:** **`$158.29 USD`**

### Schematic 
<img width="1112" height="725" alt="image" src="https://github.com/user-attachments/assets/87047980-2da0-419c-89de-629a7c5ac858" />




### PCB Design

<img width="515" height="723" alt="Screenshot 2026-08-17 012205" src="https://github.com/user-attachments/assets/270fe80f-59ab-4466-8e6e-7eb239a38999" />
<img width="467" height="777" alt="Screenshot 2026-08-17 012254 - Copy" src="https://github.com/user-attachments/assets/d9190034-1c50-402e-98b3-393a6d17cfcb" />

### 3D Design

<img width="790" height="757" alt="Screenshot 2026-08-09 231012" src="https://github.com/user-attachments/assets/3dbbf17c-30e3-4e49-9bf2-d1b93e53c15c" />
<img width="656" height="611" alt="Screenshot 2026-08-09 225355" src="https://github.com/user-attachments/assets/7e27f814-4efe-4a22-ad8d-974c266047d8" />

 
