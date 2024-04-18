# Cisco Device Configuration Backup Script

This Python script allows you to back up the running configuration of Cisco devices such as switches and routers via a serial connection.

## Introduction

This script provides a simple yet effective way to automatically back up the running configuration of Cisco devices. It establishes a serial connection with the device, enters privileged EXEC mode if required, retrieves the running configuration, and saves it to a specified file.

## How It Works

The script utilizes the `serial` library to establish a connection with the Cisco device through a COM port. It sends necessary commands to the device to enter privileged EXEC mode and fetches the running configuration using the `show running-config` command. Finally, it saves the configuration to a specified file.

## Features

- Establishes a serial connection with Cisco devices.
- Automatically enters privileged EXEC mode if required.
- Retrieves the running configuration.
- Saves the configuration to a specified file.

## Getting Started

1. Connect the Cisco device to your computer using a serial cable.
2. Make sure Python is installed on your system.
3. Run the script.
4. Enter the COM port number, BAUD rate, password (if required), and output file name as prompted.
5. The running configuration will be saved to the specified file.

## Dependencies

- Python 3.x
- pyserial library

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).
