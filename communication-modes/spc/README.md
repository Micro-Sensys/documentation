# SPC (Script programmed communication) mode
This communication mode consist on a script based communication. The script running on the device controls the behavior/functionality of the RFID reader.
Communication with the host device is also defined by the script.

## Characteristics
* Uni-directional or bi-directional communication
	* For uni-directional, keyboard emulation is an option
* Protocol based or no-protocol
* Device visualization control (LED or display when available)

## Target applications
This mode is most apropriate for scan applications, but also read/write applications are possible. It moves most of the intelligence to the reader, so that applications are easier to develop and require less code and complexity.
Some types of possible applications:
* Scan applications with uni-directional communication flow
	* The scan functionality is defined in script
	* Scan can be continuous or triggered on device (when trigger functionality available. For example a key)
	* Scanned information is formatted and sent to host device using:
		* Keyboard emulation: Using Bluetooth HID or USB HIDconverter -> *No software needed*
		* Serial communication: with or without protocol
* Machine triggered applications (for example PLC systems)
	* The scan functionality is defined in script
	* Scan can be continuous or trigger with a command
	* Scanned information is formatted and sent to the PLC communication bus with the desired format

## Supported readers
All Micro-Sensys readers from the *space* series support this mode.

## Default mode for
RFID readers with Bluetooth interface are by default provided in Bluetooth HID (keyboard emulation) mode running a script

## Software examples
For Bluetooth HID mode there is no software needed to test this functionality. Just conect the device to your host device, open any software (text editor, Microsoft Excel, website, ...) where the scanned data should be written.
If you are interested in serial communication, you can check any of our MPC sample codes. Let us know if you need further support
	
## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
