# TrashTalker - Smart Recycling Bin Sorter

A smart recycling bin that automatically classifies waste into 4 categories: plastic, metal, cardboard, and trash.

## Features

- ESP32-S3 Camera for real-time waste detection
- AI Classification using GPT-5 vision API
- Audio Feedback to guide users
- Network Connected with CoAP integration
- Automated Sorting for sustainable waste management

## Quick Start

See the [project slides](https://docs.google.com/presentation/d/18R6MJeCCg-8uaThV88Z-llwF2COXKAZdhlyq_RTMkm0/edit?usp=sharing) for full details, architecture, and setup instructions.

## Project Structure

- `firmware/` - ESP32-S3 Arduino code
- `coap-server/` - Python CoAP server and serial bridge
- `camera_test/` - Camera testing utilities
- `bridge_to_s3.py` - AWS S3 bridge module
- `sdkconfig.defaults` - ESP32 configuration

## Getting Started

1. Flash the firmware to your ESP32-S3
2. Install Python dependencies: `pip install -r requirements.txt`
3. Run the CoAP server bridge

For detailed setup, visit the [project presentation](https://docs.google.com/presentation/d/18R6MJeCCg-8uaThV88Z-llwF2COXKAZdhlyq_RTMkm0/edit?usp=sharing).

---

SodaHacks 2026 Sustainability Track Winner
