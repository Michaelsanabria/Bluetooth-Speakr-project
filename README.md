# Bluetooth-Speakr-project

Open Source Bluetooth Speaker

The Open Source Bluetooth Speaker project aims to create a fully customizable, modular, and energy-efficient wireless speaker system that connects seamlessly with other speakers through a mesh network.
This allows users to synchronize multiple speakers and stream audio from any Bluetooth-enabled device with minimal latency.

🌟 Core Purpose

This project’s mission is to democratize audio engineering by providing an open platform for learning, collaboration, and innovation.
Whether you’re a hobbyist, student, or hardware developer, this system offers a foundation to explore embedded audio design, wireless communication, and low-power optimization techniques.

🧠 **Main Technologies** <!-- Must be in bold -->

	•	Bluetooth Low Energy (BLE) – for wireless audio streaming and device connectivity
	•	Mesh Networking Protocols – to connect multiple speakers and share audio data
	•	Flux.AI / KiCad – for PCB design and circuit schematics
	•	C / C++ – for embedded firmware development
	•	Python / Node.js – for control interfaces and configuration tools
	•	USB-C Power System – with integrated low-power management and battery monitoring


## Bill of Materials (BOM) 
<!-- working on building a table with BOM used in project --> 
| **Item No.** | **Component Name**      | **Part Number**       | **Description / Function**           | **Quantity** | **Manufacturer** | **Supplier / Link** | **Unit Cost (USD)** | **Total Cost (USD)** | **Notes** |
|---------------|--------------------------|------------------------|--------------------------------------|---------------|------------------|----------------------|----------------------|-----------------------|-----------|
| 1             | ESP32-S3-WROOM-1         | ESP32-S3-WROOM-1-N8R2 | Wi-Fi + Bluetooth SoC Module         | 1             | Espressif        | [DigiKey](https://www.digikey.com) | 5.20 | 5.20 | Main MCU / wireless control |
| 2             | Audio Amplifier IC       | TPA3116D2              | Class-D stereo audio amplifier       | 1             | Texas Instruments| [Mouser](https://www.mouser.com) | 3.10 | 3.10 | Drives speakers |
| 3             | Speaker Driver (Full-Range) | ND65-8               | 2.5" 8Ω 15W full-range driver        | 2             | Dayton Audio     | [Parts Express](https://www.parts-express.com) | 7.50 | 15.00 | Stereo setup |
| 4             | Battery (Li-ion 3.7V)    | NCR18650B              | Rechargeable battery cell            | 2             | Panasonic        | [Battery Junction](https://www.batteryjunction.com) | 6.00 | 12.00 | Power source |
| 5             | Battery Charging IC      | TP4056                 | Li-ion battery charger (USB-C input) | 1             | NanJing Top Power| [AliExpress](https://www.aliexpress.com) | 1.00 | 1.00 | For safe charging |
| 6             | USB-C Connector          | 105444-0101            | USB-C Receptacle (Power + Data)      | 1             | Molex            | [DigiKey](https://www.digikey.com) | 0.85 | 0.85 | Input connector |
| 7             | Power Regulator (5V)     | AMS1117-5.0            | Linear voltage regulator 5V output   | 1             | Advanced Monolithic | [Mouser](https://www.mouser.com) | 0.40 | 0.40 | Powers logic circuits |
| 8             | PCB                      | —                      | Custom-designed 2-layer PCB          | 1             | —                | —                    | 10.00 | 10.00 | Designed in Flux AI |
| 9             | Passive Components Kit   | —                      | Resistors, capacitors, headers, etc. | 1 set         | —                | —                    | 5.00 | 5.00 | Assorted |
| 10            | Enclosure                | —                      | 3D printed or injection molded case  | 1             | —                | —                    | 7.00 | 7.00 | Design in Blender |
| **Total**     |                          |                        |                                      |               |                  |                      |                      | **59.55**             |           |



## Documentation

- <a href = "https://www.notion.so/29a2251ec6b980baaedec4d5eed506ad?v=29b2251ec6b9801b9faf000ce8ff7c8a&source=copy_link"> Notion <a>















