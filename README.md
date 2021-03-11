# Exchange-15-GEC
 
Custom Version of Install-Exchange 15 Script from michelderooij

https://github.com/michelderooij/Install-Exchange15

New Parameters:

-Hostname STRING 

Used for setting the hostname in post config

-OutlookHostname

Used for Exchange URL (like outlook.example.org)

-AutodiscoverHostname 

Used for Exchange URL (like autodiscover.example.org)

-ExchangeProductKey 

Exchange Product Key


New Functions:
Includes Hafnium patches
Patches whole system with PSWindowsUpdate 


ToDo:


Import Certificate
Copy DB to original path
DB Mount


Disclaimer:
This Script fucks up Exchange-15 script and customizes it to only recover Exchange after HAFNIUM infection on new server with all requiered parameters
