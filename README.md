# wifi_tools


Please run  
==========
```
$wpa_supplicant -Dwext -i<Your wireless device name> -c<.conf file>  
$sudo dhcpcd <Your wireless device name>  
```
Or   
==
```
$wpa_supplicant -Dnl80211 -i<Your wireless device name> -c<.conf file>  
$dhcpcd <Your wireless device name> 
```
