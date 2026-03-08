# ESP32-S3 Firmware

Arduino firmware for material classification on ESP32-S3.

## Setup

1. Install Arduino IDE
2. Add ESP32 board support (https://github.com/espressif/arduino-esp32)
3. Select ESP32-S3 board
4. Upload the firmware to your device

## Output Format

The firmware outputs material classifications in the format:
```
>> Sorting: <material_name>
```

This output is read by the serial_bridge.py script.
