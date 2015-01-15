Learning-IoT-CoapGateway
========================

Source code for the Creating protocol gateways chapter of the book [Learning Internet of Things](https://www.packtpub.com/application-development/learning-internet-things).

This chapter covers the basics of how to build protocol gateways by using the Internet of Things service platform Clayster. It shows the benefits of using a well-defined hardware abstraction model available in such a platform, to make devices interoperate across protocols.

The source code contains the following projects:

|Project                          | Description|
|:------------------------------- |:---------- |
|**CoapGateway**                  | A CoAP gateway project, making it possible to use CoAP devices, as well as publish existing devices accessible to the Clayster platform, using the CoAP protocol. This project makes it possible to bridge commands made on different protocols supported by other modules (such as XMPP, MQTT, etc.) and CoAP.|

The project is developed in C# and compiled using [Xamarin](http://xamarin.com/). It is executed on a Raspberry Pi using [MONO](http://www.mono-project.com/). The project does not use any code specific to the Raspberry Pi, and can therefore be run on any system executing .NET code.

To compile, the project needs you to download a distribution of [ClaysterSmall](http://www.clayster.com/downloads) platform and install it in `C:\Downloads\ClaysterSmall`. If you install it anywhere else, you must update and external references found in the `CoapGateway\CoapGateway.csproj` project file locally.

Chapters of the book:

| Chapter | Title                         | Source Code |
| -------:|:----------------------------- |:-----------:|
|         | Preface                       | N/A |
| 1       | Preparing our IoT projects    | N/A |
| 2       | The HTTP Protocol             | [Learning-IoT-HTTP](https://github.com/Clayster/Learning-IoT-HTTP) |
| 3       | The UPnP Protocol             | [Learning-IoT-UPnP](https://github.com/Clayster/Learning-IoT-UPnP) |
| 4       | The CoAP Protocol             | [Learning-IoT-CoAP](https://github.com/Clayster/Learning-IoT-CoAP) |
| 5       | The MQTT Protocol             | [Learning-IoT-MQTT](https://github.com/Clayster/Learning-IoT-MQTT) |
| 6       | The XMPP Protocol             | [Learning-IoT-XMPP](https://github.com/Clayster/Learning-IoT-XMPP) |
| 7       | Using an IoT Service Platform | [Learning-IoT-IoTPlatform](https://github.com/Clayster/Learning-IoT-IoTPlatform) |
| 8       | Creating protocol gateways    | [Learning-IoT-Gateway](https://github.com/Clayster/Learning-IoT-Gateway) |
| 9       | Security and Interoperability | N/A |
