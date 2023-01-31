# ApiDiscovery

To demonstrate APIs or to just have a look at what information you can retrieve from HPE Storage APIs you'll need to have:
- some programming knowledge
- a programming language installed, like curl, Python, etc.
- knowledge about the authentication process of the HPE Storage device

To remove these prerequisites an app called ApiDiscovery has been developed. ApiDiscovery is a C# compiled executable that does not need to be installed, it can be run from a removable device, when preferred. The app has a simple Graphical User Interface (GUI) and will only run APIs that collect information; it will not alter the configuration of the HPE storage device (you can instruct the ApiDiscovery tool to run an API to create or delete an object on an HPE storage device, however that will result in an error message). This limitation is by design, and has been implmented to make the app non-intrusive and reduce the risks.

So, the tool is to demonstrate HPE storage APIs or to offer people a simplified "first look" at HPE storage APIs, it is NOT a tool to manage or automate tasks for HPE Storage devices.

### Instructions: 
Unzip and run the ApiDiscovery.exe (no installation required)
### Supports:
- 3PAR
- Nimble
- Primera
- Alletra 6000
- Alletra 9000
- HPE Data Storage Cloud Console (DSCC)
- HPE InfoSight
- HPE SAN switches (Broadcom)
