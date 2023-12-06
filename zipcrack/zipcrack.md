# zipcrack

En kilde i DarkCorp har givet dig en zipfil som er beskyttet med et kodeord. Tit vælger vi kodeord ud fra ting vi godt kan lide. Han ved at personen som har fået filen stjålet er stor fan af jokeren fra filmen *The Dark Knight*. Brug jokerens fanside som ordbog over kodeord som han kunne have brugt:

		->		
		https://batman.fandom.com/wiki/The_Joker_\(Nolanverse\)

## Fremgangsmåde
1. Brug cewl til at lave en ordbog fra hjemmesiden
2. Brug fcrackzip til at lave et brute force angreb på zipfilen

## cewl

		Eksempel:
		cewl https://google.com/ -d 0 -w minOrdbog

## fcrackzip

		Eksempel:
		fcrackzip -u -D -p minOrdbog -v låstfil.zip