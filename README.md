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

## What are its use-cases?
The BLE Bloodhound was designed for the following 4 main ideas:
 1. **IT and Cybersecurity Professionals testing their infrastructure.**
 2. **Use in Law Enforcment** (i.e. rescue, and retrieving stolen or evidential assets)
 3. **Help detect cheating in education systems** (i.e. written, closed book exams).
 4. **Detect foreign tracking devices** (i.e. An attacker's Airtag planted on your car/purse).

 That said, its usage **MUST be used for ethical purposes only**. Failure to do so can lead to prosecution by your local authorities. For more information on usage and guidelines, visit ...
