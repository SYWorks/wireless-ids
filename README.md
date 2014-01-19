Wireless-IDS
============

This tool works in Linux environment and required Aircrack-NG suite and TShark to be present in the system which is readily available in BT and Kali.
 
Basically the tool will use a wireless interface to capture all the surrounding network traffic and analysed for suspicious activity for
- Detecting mass deauth sent to client/access point to detect possible WPA attacks..
- continual sending data to access point using broadcast MAC address which indicate a possibility of WEP attacks 
- continual communication between client and access point using EAP authentication which indicate the possibility of WPS bruteforce attack by Reaver/WPSCrack

At present, it detect this 3 possible attack. I am in the process of adding new function which will detect changes in wireless client connected to another access point (possibility of connected to a Rogue AP). 

Screenshot can be found at https://www.facebook.com/media/set/?set=a.767725556588881.1073741830.281645261863582

To run the script, type
‘Python wids.py’
Or
‘chmod +x wids.py’
‘./wids.py’

For help, type ‘./wids.py --help’

To check/upgrade, type ‘./wids.py --upgrade’
