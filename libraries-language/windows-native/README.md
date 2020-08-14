# Windows native libraries
Here is a list of libraries implemented in C++ and compiled as a Windows native dll.

These libraries can be used in a variety of programming languages, but always for software to run on Windows
Depending on the functionality implemented there are two libraries

## iID® driver engine
For communication with RFID reader
* [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20driver%20engine%20-%20Native%20driver/APIDoc_iIDDriver3000PRO_1059_E.pdf)
* [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20driver%20engine%20-%20Native%20driver/)
* Sample codes
    * [samples-doc_transponders_windows](https://github.com/Micro-Sensys/samples-doc_transponders_windows) *native* folder
    * [samples-doc_telidtransponders_windows](https://github.com/Micro-Sensys/samples-doc_telidtransponders_windows) *native* folder

## TELID3xx Native
For interacting (read, programm, ...) TELID®300 data loggers (currently supported TELID®311 and TELID®343)
* [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/TELID300%20-%20native%20library/APIDoc_TELID3xx_native_driver_TP_16_E.pdf)
* [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/TELID300%20-%20native%20library/)
* Sample codes
    * [samples-doc_telidloggers_windows](https://github.com/Micro-Sensys/samples-doc_telidloggers_windows)

## Integration steps
For Windows native libraries, they should just be accessible to your software at runtime. You should add the function definitions in your code to be load dynamically.

There are some ways to achieve this. Some examples:
* Add them in the folder where the final EXE is located. This should be enough for Windows to be able to find it and access it
* Install it in the computer in one of the *default* location for DLLs (for example *Windows* folder)

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
