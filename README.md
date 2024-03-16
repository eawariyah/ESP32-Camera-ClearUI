# ESP32 Camera ClearUI

This repository contains a clean user interface (UI) design for the ESP32-CAM module. The ESP32-CAM is a versatile Wi-Fi enabled microcontroller with an integrated camera, making it an ideal platform for various IoT and surveillance projects.

## Features

- **Clean UI Design**: The user interface is designed to be simple, intuitive, and visually appealing.
- **Responsive Layout**: The UI is optimized for both desktop and mobile devices, ensuring a consistent experience across different screen sizes.
- **Customizable Settings**: Users can easily configure camera settings, such as resolution, frame rate, and compression level, directly from the UI.
- **Real-time Streaming**: Live video streaming from the ESP32-CAM to a web browser is supported, allowing users to monitor their surroundings in real-time.
- **Snapshot Capture**: Users can capture snapshots from the live video stream with a single click, enabling quick image capture for surveillance or monitoring purposes.
- **Easy Integration**: The UI can be easily integrated into existing ESP32-CAM projects or used as a standalone application for camera control and monitoring.

## Getting Started

To use the ESP32 Camera ClearUI, follow these steps:

1. **Hardware Setup**: Connect your ESP32-CAM module to your development board and ensure that it is properly powered and configured.
2. **Software Setup**: Upload the necessary firmware to your ESP32-CAM using the Arduino IDE or your preferred development environment.
3. **Web Interface**: Access the web interface by entering the IP address of your ESP32-CAM in a web browser. You should see the ClearUI dashboard, where you can configure camera settings and view the live video stream.
4. **Configuration**: Customize camera settings according to your requirements. Experiment with different resolutions, frame rates, and compression levels to achieve the desired balance between image quality and network bandwidth.
5. **Monitoring**: Use the live video stream and snapshot capture feature to monitor your surroundings and capture images when needed.

## Screenshots

![Dashboard](https://github.com/eawariyah/ESP32-Camera-ClearUI/assets/109866711/75371e9c-5056-4385-acdc-7da9d39d7e0a)

<!--![Settings](screenshots/settings.png)-->

## Dependencies

- **ESP32 Libraries**: Ensure that you have installed the necessary ESP32 libraries and dependencies for camera operation and web server hosting.
- **ArduinoJson Library**: This project uses the ArduinoJson library for handling JSON data exchange between the ESP32-CAM and the web interface.

## Contributing

Contributions to the ESP32 Camera ClearUI project are welcome! If you have suggestions for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request. Together, we can make the ClearUI even better!

## License

This project is licensed under the [MIT License](LICENSE).
