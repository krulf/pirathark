# filerne

En tidligere medarbejder fra DarkCorp har givet dig en usb stick med filer fra virksomheden. Han mente det var et program der var adskilt i forskellige dele.

Du skal finde ud af hvilken rækkefølge filerne skal sættes sammen. Derefter skal du sætte filtilstandsbitten på den sammensatte fil.

 - Filer kan sættes sammen ved at bruge ```cat``` til at læse dem og sende dem over i en ny fil. F.eks. en fil der er sammensat af 2 delfiler:
 		-> ```cat filnavn1 filnavn2 > samletfil```
 - Du kan ændre en fils tilstandsbits med ```chmod```. For at kunne køre en fil skal den have sat bitten x (udfør) for dig som bruger (u):
 		-> ```chmod u+x filnavn```
 
