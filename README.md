# BFTuploader
# OctoPrint-BFTUploader

**OctoPrint-BFTUploader** is a production-ready plugin for OctoPrint that supports:

- Multi-file batch upload  
- Real-time WebSocket progress  
- MD5 / CRC32 / SHA256 verification  
- Resume support for interrupted uploads  
- Firmware auto-detection (Marlin, Klipper, Prusa, RRF)  
- Drag-and-drop UI and toast notifications  

## Installation

1. Run the builder script to generate the plugin ZIP:  
   ```bash
   python3 build_bft_production_ws_resume.py
