# BLE-Bloodhound
Firmware for ESP32 based devices, enabling for advanced tracking and locating of Bluetooth capable devices.

## How does it work?
In simple terms, the BLE Bloodhound works by listening to broadcasted Bluetooth Low Emission (BLE) signals that are actively advertising in open air. These signals are emitted by nearly every modern-age smart device due to it's convience in our connected lifestyles, and is typically measured in `RSSI` (Received Signal Strength Indicator), a unit of measure that almost directly correlates to the distance you are from a broadcasting device. Using this, we can roughly identify the proximity of almost any bluetooth device and follow the direction where their RSSI indicates the strongest connection (similar to the game "Hot and Cold").

`RSSI` is usually reported in `dBm`, which is a logarithmic unit of power.
Example:

 - `−30 dBm` → very strong signal (device is very close/arms length away)

 - `−80 dBm` → weak signal (device is far away)

 - `−100 dBm` → barely detectable

For more info on how it works, visit the ressource page for a more detailed explanation.
