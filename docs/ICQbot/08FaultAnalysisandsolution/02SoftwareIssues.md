# Software Issues

## Xiao Q Robot Unable to Connect to Software via Bluetooth  

1. Issue 1: Bluetooth Service Not Enabled. 
    1. (Android 4.0 and above) Tap the "Bluetooth" button in the phone's dropdown menu to enable the Bluetooth service.  
    2.  "Allow ICQbot to access this device's location?" ---- Always Allow.
    3. Check permissions: Go to Settings → App Management → ICQbot → Permissions, and enable location access permissions.  
2.  Issue 2: Location Services (GPS) Not Enabled.
    1. (Android 4.0 and above) Tap the "Location Services" button in the phone's dropdown menu to enable location services.  
    2. "Enable Bluetooth Service" ---- Allow.
    3. Check Bluetooth status: Go to Settings → Bluetooth to enable or disable Bluetooth.  
3. Issue 3: Location Permissions Not Set to Always Allow.
    1.  "Location services not enabled, please enable them" ---- Enable.
    2. Check hidden settings: Go to Settings → Privacy → Location Services to enable or disable location services. Tap on Location to view all enabled location-based apps.  
4.  Issue 4: Firmware Missing.

       Please update the firmware using the link provided below. [[Xiao Q Robot Firmware Upgrade]  ](https://icreaterobot-icqbot-docs.readthedocs.io/en/latest/docs/ICQbot/07Firmwareupgrade/01ICQbotXiaoQRobot.html)

5.  Issue 5: Version Mismatch  

       Check the firmware and software versions for compatibility using the links provided below. [[Software Update Log]](https://icreaterobot-icqbot-docs.readthedocs.io/en/latest/docs/ICQbot/09UpdateLog/02SoftwareUpdateLog.html)、[[Hardware Update Log]](https://icreaterobot-icqbot-docs.readthedocs.io/en/latest/docs/ICQbot/09UpdateLog/01HardwareUpdateLog.html)

**Special Note:**  
For versions 2.3.0 and earlier, Bluetooth service, location service, and location permissions must be manually enabled. Versions after 2.3.0 include a detection feature that automatically redirects users to the settings page to enable missing permissions and services.  

