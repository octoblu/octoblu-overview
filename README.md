# Octoblu
Octoblu is a full-stack Internet of Things (IoT) platform capable of automating solutions in any vertical market. Approximately 80% of our IoT stack is open source (everything in green below) with over 800 repositories available on GitHub.

Here's a simplified architecture diagram of our IoT stack and components.

![](https://octoblu.com/images/others/architecture.png)

Here's a list of the components that make up our IoT stack.

# Meshblu
Octoblu’s [Meshblu](https://github.com/octoblu/meshblu) platform is the core communication layer of our offering. It is a secure, cross-protocol scalable cloud-based system enabling communication between smart devices, sensors, cloud resources, Arduinos, Raspberry Pi’s, and any other IP based hardware device, non-IP based hardware device or software API.

# Connectors
Octoblu connects smart devices, wearable devices, sensors, cars, homes, offices, robots and web services (REST APIs) together via our global mesh network!

Our platform allows like and unlike devices to communicate using HTTP, WebSockets, MQTT, CoAP, XMPP, and AMQP. Additional protocols such as AllJoyn, BLE, SNMP etc. can be bridged into Octoblu using our Gateblu gateway. We prefer to connect things to Octoblu via their native protocols. We also connect all of Citrix's products and third-party REST APIs together.

Search for our open source plugins [here](https://github.com/search?q=org%3Aoctoblu+meshblu-).

# Designer
Octoblu’s drag-and-drop designer makes automation simple. It's powerful enough to handle complex interactions, yet simple enough for even non-engineers to use. Just drag, drop, and deploy, without ever writing a single line of code.

Engineers can extend designs beyond our out-of-the-box tools. Our designer includes a function node allowing engineers to write JavaScript routines to extend payloads etc. It also includes REST operators for interacting with private APIs. Engineers can also write Gateblu plug-ins for adding smart devices to Octoblu.

#Computing Engine
Automated workflows are stored securely and are designed to run with high availability. Our secure environments are flexible enough to run in a cloud, laptop or microcomputer, and can be hosted publicly or privately.

Everytime you press the "play" button in the designer, your automation is deployed to our real-time computing engine. It runs forever (or until you stop it).


#IoT Gateway
[Gateblu](https://github.com/octoblu/gateblu) is the Octoblu gateway offering and is the smart software hub working within the Octoblu platform connecting to Meshblu any smart device that has an IP address and any not-so-smart devices lacking an IP address. This software based hub is supported on Mac, Linux or Windows operating systems as well as iOS and Android for mobile operations.

# Analyze
Stream sensor data and machine-to-machine instant messages to bigdata stores in real-time!

Our bigdata forwarding adapters currently support Splunk, ElasticSearch, TempoIQ, InitialState, Intel Analytics, and Microsoft Analytics. As trends and anomolies are detected, these analytics platforms can call Octoblu webhooks and trigger automations to close the loop on machine learning and actions.

# Microcontroller OS
[Tentacle](https://github.com/octoblu/tentacle) is Octoblu’s Microcontroller Operating System that allows the connection of Arduino compatible devices to Meshblu with or without the use of a CPU. This allows you to control the voltage of any GPIO pin on the device as well as stream analog and digital sensor data into Meshblu.
