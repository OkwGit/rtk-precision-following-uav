Pixhawk 6C Mini • UM982 RTK • Ground/Air Rover System • LoRa/BLE Differential Link

This project is a **centimeter-level RTK follow-me UAV system** designed for photography and autonomous tracking.  
The system uses:

- **UM982 RTK (Base + Air Rover + Ground Rover)**  
- **Pixhawk 6C Mini flight controller**  
- **ArduPilot firmware**  
- **LoRa/BLE differential data link**  
- **Ground Rover + Air Rover dual-rover architecture**

### 🔹 RTK Positioning (CM-Level Accuracy)  
- UM982 based RTK Base Station  
- Air Rover outputs FIX coordinates to Pixhawk  
- Ground Rover used for relative tracking  
- Supports RTCM3 input/output

### 🔹 Autonomous Follow-Me Mode  
- Uses **Ground Rover → UAV** relative position  
- Follow distance, altitude, and heading configurable  
- ArduPilot LUA / Guided mode integration

### 🔹 Communication Architecture  
- LoRa (E22-900T33S) or BLE for diff data  
- ESP8266 MAVLink WiFi bridge (optional)  
- ELRS for RC link (Radiomaster Pocket)

### 🔹 Hardware Integration  
- Pixhawk 6C Mini  
- PM06 Power Module  
- Custom RTK Rover wiring harness  
- Optional payload: 300g lighting module or flash
