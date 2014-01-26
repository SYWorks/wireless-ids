Wireless IDS [Intrusion Detection System] 
=========================================

Wireless IDS is an open source tool written in Python and work on Linux environment. This tool will sniff your surrounding air traffic for suspicious activities such as WEP/WPA/WPS attacking packets. It do the following
* Detect mass deauthentication sent to client / access point which unreasonable amount indicate possible WPA attack for handshakes.
* Continual sending data to access point using broadcast MAC address which indicate a possibility of WEP attacks
* Unreasonable amount of communication between wireless client and access point using EAP authentication which indicate the possibility of WPS bruteforce attack by Reaver / WPSCrack
* Detection of changes in connection to anther access point which may have the possibility of connection to Rogue AP (User needs to assess the situation whether similar AP name)
* Detects possible Rogue Access Point responding to probe by wireless devices in the surrounding.


Visit [my Facebook Page](https://www.facebook.com/syworks) for other updated information and tools.

Read Wiki for installation and other details (https://github.com/SYWorks/wireless-ids/wiki)

Submit issue [here](https://github.com/SYWorks/wireless-ids/issues)
