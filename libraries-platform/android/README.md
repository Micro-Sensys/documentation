# Libraries for Android
Here is a list of libraries that can be used for Android development

* microsensysRFID - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/microsensysRFID%20-%20aar%20library/APIDoc%20MicroSensys%20iID3000%20Java%20API%20-%20Android%20E6_10.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/microsensysRFID%20-%20aar%20library/)
    * Sample codes
        * [samples-doc_transponders_android](https://github.com/Micro-Sensys/samples-doc_transponders_android)
        * [samples-doc_telidtransponders_android](https://github.com/Micro-Sensys/samples-doc_telidtransponders_android)
        * [samples-spc_android](https://github.com/Micro-Sensys/samples-spc_android)
* telid300interface - For TELID®300.nfc dataloger integration on Android using smartphone integrated NFC
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/TELID300nfc%20-%20aar%20library/APIDoc%20TELID300nfc%20%20Java%20API%20-%20Android%20E11.pdf)
    * [download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/TELID300nfc%20-%20aar%20library/)
    * Sample codes
        * [samples-doc_telidloggers_android](https://github.com/Micro-Sensys/samples-doc_telidloggers_android)
*iID®service (RESTful) - For communication with RFID reader
    * [API Documentation](https://www.microsensys.de/downloads/DevSamples/Libraries/Windows/iIDservice%20-%20RESTful/APIDoc_iIDservice_1.3_E.pdf)
    * [Android PlayStore link](https://play.google.com/store/apps/details?id=de.microsensys.iidservice)
    * [Android download link](https://www.microsensys.de/downloads/DevSamples/Libraries/Android/iIDservice%20-%20RESTful/iID%c2%aeservice_v1.3.apk)
    * [PC download link](https://www.microsensys.de/en/contacts/) *in progress*
    * Sample codes (*in progress*)


## Integration steps (using Android Studio)
Open the project where you wish to add the library.
1. Select *File* - *New Module* - *Import JAR/AAR* and select the library. It will be imported into the project
2. Select *File* - *Project structure...*
3. In this new window, navigate to *Dependencies* on the left side panel
4. Under *Modules* you should be able to see the library as a module and the module of your application (normally *app*)
5. Select the module for your application, and under *All Dependencies* press the **+** button, then select *Module Dependency* and make sure the library module is selected.

Once the library module is selected as a dependency for your application, you can access the builtin capabilities and functionalities

For RESTful services, the working process must be running in the host device where the RFID reader is connected.

## Contact
* For coding questions or questions about this sample code, you can use [support@microsensys.de](mailto:support@microsensys.de)
* For general questions about the company or our devices, you can contact us using [info@microsensys.de](mailto:info@microsensys.de)

## Authors

* **Victor Garcia** - *Initial work* - [MICS-VGarcia](https://github.com/MICS-VGarcia/)
