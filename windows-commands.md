# Windows Commands

Just some really, really basic windows commands for doing some very basic security functions.

## Active Directory 

BloodHound<br />
PingCastle<br />
PurpleKnight<br />

## Patching

winget upgrade
winget upgrade -all (or --id <idname>)<br />

## WiFi

netsh wlan show profile - this will get you a list of WiFi networks that this machine knows<br />
netsh wlan show profile name="WifiNetworkName" key=clear - get the WiFi network name from the prior command, then use it here to get the cleartext password<br />
