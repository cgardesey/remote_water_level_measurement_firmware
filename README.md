# Arduino Project: Remote water Level Monitoring

This is an Arduino project that demonstrates remote monitoring of water level in a tank. The hardware sends data to an [android app](https://github.com/cgardesey/RemoteWaterMonitoring)
The project uses the Arduino programming language and can be customised for similar projects

## Table of Contents
- [Requirements](#requirements)
- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Requirements
To run this project, you will need the following components:
- Arduino nano
- Tp4056 BMS
- Mt1306 boost converter
- Water Proof Ultrasonic sensor
- SIM800l gsm module
- Male/female headers
- Solar charge controller module
- Resistors
- Transistors
- Capacitors
- Jumper wires
- Breadboard (optional, for prototyping)

## Hardware Setup
Setup the the hardware as shown below:

![image](https://github.com/cgardesey/remote_water_level_measurement_firmware/assets/10109354/36a18bdd-a06c-41b9-bfdd-7a11466c3d7b)



## Software Setup
1. Install the Arduino IDE (Integrated Development Environment) from the [official Arduino website](https://www.arduino.cc/en/software).
2. Connect your Arduino board to your computer using a USB cable.
3. Open the Arduino IDE and select the appropriate board and port from the **Tools** menu.
4. Create a new sketch in the Arduino IDE.
5. Copy and paste the code from the `remote_water_level_measurement_firmware.ino` file into your sketch.
6. Save the sketch with a meaningful name.

## Usage
1. Upload the **remote_water_level_measurement_firmware.ino** sketch to the Arduino board by clicking the **Upload** button in the Arduino IDE.
2. The LED connected to the Arduino board should start blinking at a fixed interval.
3. Experiment with the code to and customize to suit your needs.

## Contributing
Contributions to this project are welcome. If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Submit a pull request with a clear description of your changes.

If you're looking to integrate with an android sms based project, make sure to check out the the repository corresponding to the [android project](https://github.com/cgardesey/RemoteWaterMonitoring) for detailed instructions.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute this project as needed.
