# ESP32_SmartSwitch

![altium_ha_boardonline-video-cutter com-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/104ded6e-9e0b-48da-a35c-b599b5ebdeac)

This smart switch is designed to enhance the functionality of a traditional single-pole switch.
It operates with a standard 230V AC 50Hz phase line ('L') and requires a neutral wire ('N') for proper functionality.
A current sensor with a 0–3.3V voltage output range can also be connected to the switch for power monitoring capabilities.

Please note that the hardware is currently under development, and the final design has not yet been finalized.
The Altium output job files will be made available shortly.

The standout feature of this smart switch is its ability to control a light remotely via Wi-Fi, regardless of the wall switch position — thanks to its advanced circuit design, the light can be turned on or off even if the physical switch is in the 'off' position. Support for Zigbee and Bluetooth is also planned for future updates, ensuring even greater flexibility and smart home integration.


![IMG_2277_2](https://github.com/user-attachments/assets/dbc43a17-c526-4dae-860c-15a0a14faed4)
![IMG_2291_2](https://github.com/user-attachments/assets/a8e558d1-3061-41f6-9fb4-3f04a8719905)
![IMG_2350_2](https://github.com/user-attachments/assets/8fb4ba56-bf20-4930-81f1-870e02ef36e6)

Communication and control are handled by a minimalist ESP32-S3 module, designed for easy integration with the main board containing the relays, terminal blocks, and power supply.

![altium_esp32_minimal_boardonline-video-cutter com-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/ce1eae47-0aab-41e6-a039-490801e076d3)
