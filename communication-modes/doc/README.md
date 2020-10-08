# DOC (Direct Online Communication) mode
This communication mode consist on a direct command based communication between host device and RFID reader. The host device sends commands with the apropriate protocol, and the RFID reader processes the command and sends an answer back to the host device.
The words *direct* and *online* describes this mode as the command is processed just as it is received by the reader without any delay. In this way, the reader does nothing else as wait for the next command that contains the next operation to perform.

## Characteristics
* Bi-directional
* Protocol based

## Target applications
This mode is most apropriate for applications where a full host based reader and transponder control is desired. 
Applications where read/write transponder functionality is needed, are usually implemented using this mode.
This mode also has a limited trigger support (for readers with trigger functionality)

## Supported readers
All Micro-Sensys readers support this mode.

## Default mode for
All RFID readers with only a communication interface and without trigger functionality are provided in this mode.

## Software examples
Most of free available software provided by Micro-Sensys uses this communication mode
* iID® DEMOsoft [download link](https://www.microsensys.de/downloads/SW_Install/iID%c2%aeDEMOsoft2020/Setup%20iID%20DEMOsoft%202020.exe)
	* Used to demonstrate scan, read/write and sensor functionality
* iID® interface configuration tool [download link](https://www.microsensys.de/downloads/SW_Install/iID%c2%aeDEMOsoft2020/Setup%20iID%20DEMOsoft%202020.exe)
	* Used to configure reader parameters
	
## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
