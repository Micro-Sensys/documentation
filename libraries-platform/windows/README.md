# Libraries for Windows
Here is a list of libraries that can be used for development of applications that will run in Windows systems

* iID®reader library (.NET) - For communication with RFID reader
    * DOC
        * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iIDReaderLibrary%20-%20.NET%20library/APIDoc_DocInterfaceControl_1.0_E.pdf)
        * [download link - DOC](https://www.nuget.org/packages/Microsensys.iIDReaderLibrary.DocInterfaceControl/)
        * Sample codes
            * [samples-doc_telidtransponders_windows](https://github.com/Micro-Sensys/samples-doc_transponders_windows) *dotnet* folder
            * [samples-doc_transponders_windows](https://github.com/Micro-Sensys/samples-doc_telidtransponders_windows) *dotnet* folder
    * SPC
        * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iIDReaderLibrary%20-%20.NET%20library/APIDoc_SpcInterfaceControl_1.0_E.pdf)
        * [download link - SPC](https://www.nuget.org/packages/Microsensys.iIDReaderLibrary.SpcInterfaceControl/)
        * Sample codes
            * [samples-spc_unix](https://github.com/Micro-Sensys/samples-spc_unix) *dotnet* folder 
* microsensysRFID (Java) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/microsensysRFID%20-%20jar%20library/APIDoc%20MicroSensys%20iID3000%20Java%20API%20-%20Windows%20E6_6.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/microsensysRFID%20-%20jar%20library/)
    * Sample codes
        * [samples-doc_transponders_windows](https://github.com/Micro-Sensys/samples-doc_transponders_windows) *java* folder
        * [samples-doc_telidtransponders_windows](https://github.com/Micro-Sensys/samples-doc_telidtransponders_windows) *java* folder
        * [samples-spc_windows](https://github.com/Micro-Sensys/samples-spc_windows) *java* folder
* iID®service (RESTful) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iIDservice%20-%20RESTful/APIDoc_iIDservice_1.3_E.pdf)
    * [Android PlayStore link](https://play.google.com/store/apps/details?id=de.microsensys.iidservice)
    * [Android download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/iIDservice%20-%20RESTful/iID%c2%aeservice_v1.3.1.apk)
    * [PC download link](https://www.microsensys.de/en/contacts/) *in progress*
    * Sample codes (*in progress*)
        * [samples-doc_transponders_windows](https://github.com/Micro-Sensys/samples-doc_telidtransponders_windows) *restful* folder
        * [samples-spc_windows](https://github.com/Micro-Sensys/samples-spc_windows) *restful* folder 
* iID® MPC library (.NET Framework) - For communication with RFID reader in MPC mode
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20MPC%20-%20.NET%20library/APIDoc_microsensysMPC-1.2.0.0-E.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20MPC%20-%20.NET%20library/)
    * Sample codes
        * [samples-mpc_windows](https://github.com/Micro-Sensys/samples-mpc_windows) *dotnet-framework* folder

### Obsolete - no longer supported
* iID® driver engine (Windows native) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20driver%20engine%20-%20Native%20driver/APIDoc_iIDDriver3000PRO_105A_E.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iID%20driver%20engine%20-%20Native%20driver/)
    * Sample codes
        * [samples-doc_transponders_windows](https://github.com/Micro-Sensys/samples-doc_transponders_windows) *native* folder
        * [samples-doc_telidtransponders_windows](https://github.com/Micro-Sensys/samples-doc_telidtransponders_windows) *native* folder
* TELID3xx Native (Windows native) - For interacting (read, programm, ...) TELID®300 data loggers (currently supported TELID®311 and TELID®343)
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/TELID300%20-%20native%20library/APIDoc_TELID3xx_native_driver_TP_16_E.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/TELID300%20-%20native%20library/)
    * Sample codes
        * [samples-doc_telidloggers_windows](https://github.com/Micro-Sensys/samples-doc_telidloggers_windows)

## Integration steps
For .NET Framework libraries, just add them as a reference to your project. Once you do this, you can access the builtin capabilities and functionalities.

For Java libraries, just add them to your project and be sure to include them (or its build path) in the *build* process. Once you do this, you can access the builtin capabilities and functionalities

For RESTful services, the working process must be running in the host device where the RFID reader is connected.

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
