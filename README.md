MissVenom
=========

Standalone multifunctional proxy for WhatsApp in .NET

![MissVenom](https://dl.dropboxusercontent.com/u/68235039/venom.jpg)

Using modified WebServer library 2.0 from http://webserver.codeplex.com/

Using ARSoft.Tools.Net from http://arsofttoolsnet.codeplex.com/

Not compatible with Android 2.x (does not support installing root certificates)

###Root/jailbread/unlock not required###

Usage (v1.1.4.0):
- Make sure your mobile device is on the same WLAN subnet as your machine
- Unregister WhatsApp app on your device (e.g. wipe app data)
- Start MissVenom.exe
- Set DNS address on your device to the displayed IP address (in WiFi->Static IP configuration)
- Open your device's browser and go to https://cert.whatsapp.net to install root certificate
- Open and register WhatsApp on your device
- Your identity and password will appear in MissVenom as well as in MissVenom.log
- Don't forget to turn off static IP address and reconnect to WiFi afterward!

TODO:
- TCP stream capture (currently working on)
- Deserialize GET and JSON for nice formatting (fancy fancy)
- ARP spoofing (making your life easier, one commit at a time)
