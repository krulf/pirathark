# logind

Du har fundet ud af at darkCorp har et åbent gæstenetværk der har ESSID `DarkCorp_Guest`. Du kan se om netværket er oppe med kommandoen `nmcli dev wifi list`.

Da det bare er et gæstenetværk er koden almindeligt kendt som bluepill. Kan du logge på?

For at logge på et wifi skal du bruge `nmcli`

		->
		Eksempel:
		nmcli dev wifi connect 'ESSID'