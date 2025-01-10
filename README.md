# Home-automation-using-google-assistant
This project demonstrates how to use the Google Assistant SDK and Python to automate home devices. The example provided controls a smart light, but you can extend the code to control other devices like smart plugs, thermostats, and more.
Home Automation Using Google Assistant

Overview This project demonstrates how to use the Google Assistant SDK and Python to automate home devices. The example provided controls a smart light, but you can extend the code to control other devices like smart plugs, thermostats, and more.

Prerequisites

A Raspberry Pi or any other compatible device.

Google Assistant SDK installed and configured. Follow the official guide for installation.

Smart devices to control (e.g., smart light).

Setup

Install the Google Assistant SDK on your device.

Create and download the OAuth 2.0 credentials file and save it as credentials.json.

Install necessary Python libraries:

bash
pip install google-assistant-library
pip install google-assistant-grpc
pip install google-auth
Running the Code

Save the Python code provided above in a file named home_automation.py.

Run the script:

bash
python home_automation.py
Use voice commands like "Turn on the light" and "Turn off the light" to control your smart light.

Extending the Project You can extend this project to control other smart devices by adding more commands in the execute_command method and implementing corresponding methods to control those devices.
