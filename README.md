# ESP32 WebSocket Chat Server

A simple ESP32-based chat server using WebSocket and HTTP. Clients can connect to the web interface, send/receive messages in real-time, and interact with up to 5 clients. Includes basic authentication, message rate limiting, and a lightweight design suitable for low-power applications.

## Features:
- Real-time chat using WebSocket.
- Basic authentication with username and password.
- Message rate limiting to prevent spam.
- Supports up to 5 simultaneous clients.
- Lightweight, suitable for low-power applications.

## Requirements:
- ESP32 development board.
- Arduino IDE with ESP32 support installed.
- A Wi-Fi network for the ESP32 to connect to.

## How to Use:
1. Upload the code to your ESP32 board using Arduino IDE.
2. Modify the `ssid` and `password` variables in the code to connect the ESP32 to your Wi-Fi network.
3. After the ESP32 connects, access the web server by navigating to the ESP32's IP address in a browser.
4. Send and receive messages through the web interface.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors:
- me -- кулебяка/Hideaku WisL0v
