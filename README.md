**Controlling Laptop's cooling Fan's speed to maintain temperature.**

#Description:
This repository houses Python scripts for Raspberry Pi GPIO-based fan control utilizing PWM modulation. The provided scripts offer nuanced control mechanisms based on CPU temperature:
1. Time-Dependent Control: The script dynamically adjusts the fan speed in response to CPU temperature, with time-specific configurations for efficient thermal management during different periods of the day.
2. Threshold-Based Control: The script allows users to set temperature thresholds, automatically adjusting the fan speed using PWM modulation to strike a balance between cooling effectiveness and noise reduction.

#Technical Highlights:
1. Utilizes the gpiozero library for simplified GPIO control.
2. Implements PWM modulation through the RPi.GPIO library for precise fan speed adjustments.
3. Provides adjustable parameters such as temperature thresholds and PWM duty cycles for fine-tuning based on specific hardware requirements.
4. A modular and extensible solution suitable for Raspberry Pi projects requiring active thermal control.
   
This repository aims to offer a technically robust and adaptable solution for Raspberry Pi enthusiasts seeking effective fan control mechanisms for temperature management.
