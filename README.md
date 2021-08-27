# Software-Koenighaus
Software
Update 1.04


+Button Performace

+NTP Time.

+Time Zone Fixed

+If WiFi is disconnected on screen is "noSignal" (No Icon :Design Stuff)

+Fixed issue with "Menu Time Settings" Hour was locked from (4-23) now its (0-23).

+Fixed issue with Program "Kuche" now LCD showing the actual Temperature and Program is goig like it must be in preset mode.

+Fixed issue with black Squares from prev. menu in Main Menu.

+fixed NTP server: pool.ntp.org (NTP WILL SETUP AUTOMATIC HOUR 60 sec after you connect Thermostat to WLAN

+Information on screen about Too Hot Panel :

if panel go to hi temp = 130.0 Celsius Deg. panel send the message to heater he is too hot 130+

+added saving macAddress 

+fixed Avarage Temperature in Statistic Menu;
//

//

//

//

//

//

//

//

//








Software
Update 1.06

+Local Domain (Device ID) will be the same as Device AP ex. koenighausv76cs6.local/App (koenighaus =>v76cs6<= .local) =>DEVICE ID<=    

(That will help auto pairing mesh in one network)


You Can See name of domain in "SYSTEM INFORMATION" MENU in Thermostat Device.

+added new Mqtt Messages 

+added Time syyncro with RTC memory

/// I decided to get rid of RTC chip its too expensive;

+Serial Port is unlocked so can be some issues during usage

+added WIFI TIMEZONE_US for keys but regular TIMEZONE is setup on +2

+added passwords to AP (Mobile phone always automatic connect to wifi without pass so i decided to add some simple pass)

WIFI PASSWORD:

PASSWORD FOR PANEL:12345678

PASSWORD FOR THERMOSTAT:123456789

+local domain now will be the same as SSID (WIFI NAME). That should help autopairing system.

+added security certs 

+Open Window Function is added 

/

/

/

/

/

Update 1.07

+Thermostat change range from 5-30 celsius;

+ Ip numeber in Main Menu is no longer shown

