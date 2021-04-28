# Coding Homework
Nrf52840 EVB bring up:

## Tools/HW:
* nRF52840 DK
* SW SDK - https://www.nordicsemi.com/Software-and-tools/Software/nRF5-SDK/Download
* Sensor - ADXL362 https://reference.digilentinc.com/reference/pmod/pmodacl2/start
* Jumper wires

## Requirements:
* Enable USB CDC COM port
* Stream out ADXL to USB CDC COM port
* Able to use the terminal(like coolterm or something) to see the streaming data. 
* Output string format on screen: printf(“(%d, %d, %d)\n”, x, y  z)
* Able to use the Lightblue app to read the latest (x, y, z) value. (optional)
* Shell command to start/stop streaming (optional)
* Provide the firmware image
* Upload to code to the github. You can choose:
    * Provide the repository for downloading 
    * Use this repository https://github.com/pyang-jhh/code_homework.git. You need provide your github ID for enabling the permission
* Provide working time on this project.
