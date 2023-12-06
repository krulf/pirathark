# wifihack

Du har fået navnet på darkCorps interne wifi har ESSID `DarkCorp_International` og du har fundet et dump af noget hjemmeside som måske kan bruges som ordbog. Du har lagt den lokalt på adressen http://localhost:3000/. Prøv at åbne den med `xdg-open http://localhost:3000/`.

## Hack wifi netværket
 - Brug `cewl` til at generere en ordbog
 - Brug `wifite` til at lave et brute force angreb på netværket
 
## cewl

	Eksempel:
	cewl https://google.com/ -d 0 -w minOrdbog

## wifite

	Eksempel:
	sudo wifite -e [ESSID] --dict [filnavn-til-ordbog]

## find koden

 - Når wifite har kørt viser den koden til wifi: *skriv den ned!*
 - wifite viser hvilke kommandoer du skal skrive for at genetablere forbindelsen til wifi
 - opret forbindelse til wifi og brug koden du har noteret ned	
 - nmcli dev wifi connect 'ESSID'