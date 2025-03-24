# Auto Power-Cut System

## Overview

The **Auto Power-Cut System** is an innovative solution designed to enhance energy efficiency by automatically disconnecting electrical power in unoccupied areas. Leveraging motion detection technology, this system ensures that electricity is conserved by cutting off power when no movement is detected, thereby promoting sustainable energy.
## Features

- **Motion Detection:** Utilizes Passive Infrared (PIR) sensors to detect human presence.
- **Automated Power Control:** Automatically disconnects power when no motion is detected for a specified duration.
- **Energy Efficiency:** Reduces unnecessary electricity consumption in unoccupied spaces.

## Components

- **Arduino Microcontroller:** Serves as the brain of the system, processing sensor inputs and controlling outputs.
- **PIR Sensors:** Detect motion by sensing infrared radiation changes.
- **Relay Module:** Controls the connection and disconnection of electrical power to appliances.

## How It Works

1. **Motion Detection:** PIR sensors continuously monitor the area for movement.
2. **Signal Processing:** When motion is detected, the sensor sends a signal to the Arduino.
3. **Power Control:** The Arduino activates the relay to supply power. If no motion is detected for a predefined period, the Arduino deactivates the relay, cutting off power.


## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Sanjay-bhau/Auto-power-cut-system.git
   cd Auto-power-cut-system
   
2. **Open the Arduino Sketch:**
   Launch the Arduino IDE.​
   Open the PBL_Project.ino or PBL_UPGRADE.ino file from the cloned repository.

3. **Upload the Code:**
   Connect your Arduino board to your computer.​
   Select the appropriate board and port from the Arduino IDE.​
   Upload the sketch to the Arduino.

4. **Assemble the Hardware:**
   Connect the PIR sensor to the Arduino as per the pin configuration in the code.​
   Connect the relay module to control the electrical appliances.

5. **Power the System:**
   Once everything is connected, power the Arduino. The system will start monitoring for motion and control power accordingly.

**Usage Notes**
  Sensitivity Adjustment: The PIR sensor's sensitivity and delay time can be adjusted to suit different environments.​
  Safety Precautions: Ensure that all electrical connections, especially those involving high voltage, are handled with care and proper insulation to prevent accidents.

**Applications**
  Residential Spaces: Automatically turn off lights and appliances in unoccupied rooms.​

  Commercial Buildings: Manage energy consumption in offices, conference rooms, and restrooms.​

  Public Facilities: Enhance energy efficiency in areas like libraries, waiting rooms, and corridors.​

**Contributing**
  Contributions to enhance the system's functionality are welcome. Feel free to fork the repository, make modifications, and submit pull requests.

**License**
  This project is open-source and available under the MIT License.
