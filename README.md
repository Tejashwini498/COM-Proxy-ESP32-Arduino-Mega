# COM-Proxy-ESP32-Arduino-Mega
Serial COM proxy that reads data on one UART port and forwards complete frames to another. Detects frames using start byte 0x57 and end byte 0x15. Implemented for both ESP32 (GPIO16/17 and GPIO2/4) and Arduino Mega (Serial1/Serial2). Includes buffer overflow protection, hex debug logging, and full pin wiring details
