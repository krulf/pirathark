# wifihack

Du har fået navnet på darkCorps interne wifi har ESSID `DarkCorp_Internal` og du har fundet et dump af noget hjemmeside som måske kan bruges som ordbog. Du har lagt den lokalt på adressen http://localhost:3000/. Prøv at åbne den med `xdg-open http://localhost:3000/`.

Hack wifi netværket
 - Brug `cewl` til at generere en ordbog
 - Brug `wifite` til at lave et brute force angreb på netværket
 
## cewl

		Eksempel:
		cewl https://google.com/ -d 0 -w minOrdbog

## wifite

		Eksempel:
		sudo wifite -e [ESSID] --dict [filnavn-til-ordbog]

