# MPC (Memory Packet Communication) mode
This communication mode consists on a memory packet communication between host device and RFID reader. This mode can de described on two sides:
1. RFID reader running in this mode reads the defined transponder information and saves it into its internal memory
2. Host device can read the information saved on the reader in a later point in time

## Characteristics
* Asynchronous (information is saved at one point in time, and read from device in another point in time)
* Protocol based
* TODO

## Target applications
This mode is implemented for data collector applications. The user can collect information from different points without the need of a communication link with a host device. Afterwards the reader can be connected to the host device to download the saved data.

## Supported readers
This mode is supported only by our *POCKET* models: POCKETwork (also POCKETmini for backwards compatibility)

## Default mode for
//TODO DELETE!?!
This mode is only enabled for some specific applications and is not the default mode for any reader.

## Software examples
You can test this functionality yourself using our *iID® MPC DataLoad* software.
If you don't have a POCKETwork already configured in this mode, contact us.

//TODO Describe here? In new README?
If you have a POCKETwork HF, you can just configure it using our _iID® interface configuration tool_. Please follow this steps:
1. Connect the POCKETwork to the computer 
2. Start _iID® interface configuration tool_
3. Press _Script_ button
	1. Press _Open file_ button
	2. Press _Samples_ button
	3. Select _Pwo_UID+MPC..._ script and press _OK_
4. Close _iID® interface configuration tool_
POCKETwork should be configured in MPC mode. Now just scan different transponders. Afterwards you can use our *iID® MPC DataLoad* (or any of our MPC samples) to download the data to your computer.
(For software download check [Useful Links](#Useful-links))

## Useful links
* https://www.microsensys.de/en/products/rfid-readers/mobile-reader/
* iID® MPC DataLoad [download link](https://www.microsensys.de/downloads/CDContent/Install/iID%c2%ae%20POCKET.zip)

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
