# Material Classifier

ESP32-S3 based material classification system with CoAP server integration.

## Project Structure

- **firmware/**: ESP32-S3 Arduino firmware code
- **coap-server/**: Python CoAP server and serial bridge

## Getting Started

### Prerequisites
- Arduino IDE or PlatformIO (for ESP32-S3 firmware)
- Python 3.7+ (for CoAP server)

### Installation

#### ESP32-S3 Firmware
1. Upload the firmware from `firmware/` directory to your ESP32-S3 board using Arduino IDE

#### CoAP Server
```bash
cd coap-server
pip install pyserial
python3 serial_bridge.py
```

## Components

### serial_bridge.py
Reads ESP32 serial output and sends material classifications to the local CoAP server (localhost:5683).

## License
MIT
