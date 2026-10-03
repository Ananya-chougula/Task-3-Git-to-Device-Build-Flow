# Task 3 - Git to Device Build Flow

## Objective
To create a simple ESP32 LED firmware project, track changes using Git, build the firmware, and upload the final firmware to the ESP32-S3.

## Hardware Used
- ESP32-S3
- LED
- 470 ohm resistor
- Breadboard
- Jumper wires
- USB cable

## Software Used
- Arduino IDE
- Git
- Serial Monitor

## Pin Configuration
LED → GPIO 2
ESP32 GND → Breadboard GND rail

## Firmware Versions

### Version 1
LED blinks every 1 second.

### Change 1
LED blink speed changed from 1 second to 500 ms.

Git commit:
`Faster LED blink`

### Change 2
Serial Monitor messages were added.

Git commit:
`Add Serial Monitor messages`

## Git Commit History

- Initial LED firmware
- Faster LED blink
- Add Serial Monitor messages

## Final Firmware
The final firmware blinks the LED every 500 ms and prints
"LED ON" and "LED OFF" messages to the Serial Monitor at 115200 baud.

## Build and Flash
The final firmware was compiled using Arduino IDE
and uploaded to the ESP32-S3.

## Validation
The Serial Monitor displayed repeated LED ON and LED OFF messages,
confirming that the final firmware was running on the ESP32.

## Result
The Git-to-device workflow was completed from source code
and Git commits to firmware running on the ESP32-S3.