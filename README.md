# Exchange-15-GEC

Disclaimer:
This Script fucks up the Exchange-15 script and customizes it to only recover Exchange after HAFNIUM infection on new server with all requiered parameters

If you do not want to read what I have changed in the Script and just want run and forget please use the original script and then apply your patches manually.

Custom Version of Install-Exchange 15 Script from michelderooij

https://github.com/michelderooij/Install-Exchange15

New Parameters:

-OutlookHostname

Used for Exchange URL (like outlook.example.org)

-AutodiscoverHostname 

Used for Exchange URL (like autodiscover.example.org)

-ExchangeProductKey 

Exchange Product Key


New Functions:

-Includes Hafnium patches

-Patches whole system with PSWindowsUpdate 



ToDo:

-Import Certificate

-Copy DB to original path

-DB Mount




