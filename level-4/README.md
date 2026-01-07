# Level 4: Scaling up and out
To document your setup, update this sketch.

<kbd><img src="sketch.png" height="240"/></kbd>

## Goals
To finish the level, achieve these goals.

- [ ] Add a goal for MQTT integration to send sensor data to an MQTT broker or platform (e.g., Mosquitto, Adafruit IO MQTT).
- [ ] Add a step for automatic system restart after a power outage
- [ ] Add a goal for data validation (e.g., check value ranges, discard faulty readings)
- [ ] Add a goal for alarm functionality (e.g., email or push notification when CO₂ exceeds the threshold)
- [ ] Add a goal for energy optimization in continuous operation (sleep mode, sensor shutdown)

## Building blocks
To achieve the goals, use these blocks.

- [ ] Establish network connection: Set up Wi-Fi with CircuitPython 
- [ ] Connect to a cloud API: Example for REST POST with JSON data to a cloud service
- [ ] Persistent storage: Use an SD card module or internal flash to buffer data when the cloud is offline
- [ ] Visualization: Simple web dashboard with Chart.js or Grafana to display current values
- [ ] End-to-end demo: Complete example with sensor, FeatherS3, cloud backend, and web interface
- [ ] ...

## Side quests
To learn more, consider these side quests.

- [ ] Local dashboard with a small Flask app running on the local machine
- [ ] Over-the-Air (OTA) updates for firmware changes without USB
- [ ] Sensor calibration and accuracy verification
- [ ] ...
