Stworzyłem w zależności od rodzaju trybu pracy routera po dwa skrypty na dany model urządzenia Mikrotik z modemem LTE 4G.
Testowane na urządzeniach wAP ac LTE6 oraz Chateau LTE12 i 18 
Skrypty sprawdzają status modemu (rejestracji karty sim) jak i status przyznania adresacji IP

Jeżeli chcesz zmienić wyzwalanie skryptu z Scheduler co 5 minut na Netwatch który pinguje 8.8.8.8 wklej komendy z "Netwatch dla skryptów IP status.txt" 



I created two scripts for a given Mikrotik device model with a 4G LTE modem, depending on the router's operating mode.
Tested on wAP ac LTE6 and Chateau LTE12 and 18 devices

The scripts check the modem status (SIM card registration) and the IP address assignment status

If you want to change the script triggering from Scheduler every 5 minutes to Netwatch which pings 8.8.8.8 paste the commands from "Netwatch dla skryptów IP status.txt" 
