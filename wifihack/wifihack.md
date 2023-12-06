# wifihack

Du har fået navnet på darkCorps interne wifi har ESSID `DarkCorp_International` og du har fundet et dump af noget hjemmeside som måske kan bruges som ordbog. Du har lagt den lokalt på adressen http://localhost:3000/. Prøv at åbne den med `xdg-open http://localhost:3000/`.

Hack wifi netværket
 - Brug `cewl` til at generere en ordbog
 - Brug `wifite` til at lave et brute force angreb på netværket
 
## cewl

		Eksempel:
		cewl https://google.com/ -d 0 -w minOrdbog

## wifite

		Eksempel:
		sudo wifite -e [ESSID] --dict [filnavn-til-ordbog]

## Genopret forbindelsen til WiFi/ internet

Så snart du begynder at overvåge WiFi-signaler med netværkskortet, er det i `monitor mode`. Derfor bliver du koblet fra eksisterende WiFi-netværk og har ingen internetforbindelse. Hvis du vil stoppe med at overvåge WiFi signaler og koble på internettet igen skal du skifte til `managed mode` med følgende kommando:

`sudo airmon-ng stop wlan0mon`

Hvis det har været nødvendigt for wifite at slå programmet der håndterer netværk på computeren ned også, kan det startes med:

`sudo systemctl start NetworkManager`