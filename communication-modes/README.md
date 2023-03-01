# Reader communication modes
Micro-Sensys RFID readers support in general three different communication modes: DOC, SPC, MPC.
The different communication modes allows for many different applications and provides flexiblity for integration on different systems. Here you can find a general overview, for more details please check the documentation or the liked resources
> Note: Not all devices support all communication modes. Please check the device documentation to be sure your device support the desired mode

Please don't hesitate to contact us with your requirements. We will find and suggest the mode that better adapts to your requirements

### DOC (Direct Online Communication) mode
Using this communication mode, the software controlls the reader completelly. The reader just waits for a command, processes it and sends the result back.

Using this mode in your application results in bigger implementation complexity and time.
> See [DOC documentation](doc)

### MPC (Memory Packet Communication) mode
Using this communication mode, the software only reads the data saved in the reader internal memory. The read data and its format is defined in the RFID reader.
> See [MPC documentation](mpc)

### SPC (Script Programmed Communication) mode
Using this communication mode, the software can interact with the script running in the reader. The funcionality is completelly defined in the script. There are different possibilties depending on the script:
* No communication is allowed: Script just performs the defined process and no communication is possible
* Uni-direcctional communication: Script reads the defined data and sends it back to the host device
* Bi-directional communication: Script can send and receive data/information/commands to and from the host
> See [SPC documentation](spc)

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
