# Libraries for UNIX systems
Here is a list of libraries that can be used for development of applications that will run in UNIX systems

* iID®reader library (.NET) - For communication with RFID reader
    * DOC
        * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/UNIX/iIDReaderLibrary%20-%20.NET%20library/APIDoc_DocInterfaceControl_1.0_E.pdf)
        * [download link - DOC](https://www.nuget.org/packages/Microsensys.iIDReaderLibrary.DocInterfaceControl/)
        * Sample codes
            * [samples-doc_telidtransponders_unix](https://github.com/Micro-Sensys/samples-doc_telidtransponders_unix) *dotnet* folder
            * [samples-doc_transponders_unix](https://github.com/Micro-Sensys/samples-doc_transponders_unix) *dotnet* folder
    * SPC
        * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/UNIX/iIDReaderLibrary%20-%20.NET%20library/APIDoc_SpcInterfaceControl_1.0_E.pdf)
        * [download link - SPC](https://www.nuget.org/packages/Microsensys.iIDReaderLibrary.SpcInterfaceControl/)
        * Sample codes
            * [samples-spc_unix](https://github.com/Micro-Sensys/samples-spc_unix) *dotnet* folder 
* microsensysRFID (Java) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/UNIX/microsensysRFID%20-%20jar%20library/APIDoc%20MicroSensys%20iID3000%20Java%20API%20-%20UNIX%20E6_6.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/UNIX/microsensysRFID%20-%20jar%20library/)
    * Sample codes
        * [samples-doc_transponders_unix](https://github.com/Micro-Sensys/samples-doc_transponders_unix) *java* folder
        * [samples-doc_telidtransponders_unix](https://github.com/Micro-Sensys/samples-doc_telidtransponders_unix)
        * [samples-spc_unix](https://github.com/Micro-Sensys/samples-spc_unix)
* iID®service (RESTful) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iIDservice%20-%20RESTful/APIDoc_iIDservice_1.3_E.pdf)
    * [Android PlayStore link](https://play.google.com/store/apps/details?id=de.microsensys.iidservice)
    * [Android download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/iIDservice%20-%20RESTful/iID%c2%aeservice_v1.3.apk)
    * [PC download link](https://www.microsensys.de/en/contacts/) *in progress*
    * Sample codes (*in progress*)
        * [samples-doc_transponders_unix](https://github.com/Micro-Sensys/samples-doc_transponders_unix) *restful* folder
        * [samples-spc_unix](https://github.com/Micro-Sensys/samples-spc_unix) *restful* folder 

## Integration steps
For .NET Framework libraries, just add them as a reference to your project. Once you do this, you can access the builtin capabilities and functionalities.

For Java libraries, just add them to your project and be sure to include them (or its build path) in the *build* process. Once you do this, you can access the builtin capabilities and functionalities

For RESTful services, the working process must be running in the host device where the RFID reader is connected.

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
