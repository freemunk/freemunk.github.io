
## Errors
#### De computer start na de restart weer op in herstelmodus!
Dit kan gebeuren, en het is makkelijk oplosbaar. Druk op Windows Toets en R tegelijk, en typ dan `msconfig`. Druk op OK, en ga naar het tabblad `Computer opstarten`. Onderaan zie je dan "Opstarten in veilige modus". Zet dit uit, en herstart de computer.

#### Ik krijg een "toegang geweigerd" error in herstelmodus!
Dit betekent dat je school de herstelmodus in Netwerk modus heeft gezet.  Druk op Windows Toets en R tegelijk, en typ dan `msconfig`. Druk op OK, en ga naar het tabblad `Computer opstarten`. Onderaan zie je dan "Opstarten in veilige modus". Zet dit als het nog niet aan staat aan, zet dan Minimaal aan. Herstart nu de computer.

## Legaliteit
#### Is dit legaal?
Dit doen is volgens de wet legaal, aangezien er geen permanente schade op komt. Het gebruikt ook geen exploit of foutje in Windows hun code om toegang te krijgen. Check je school hun regelboek om te zien of dit tegen de schoolregels is.

#### Kan ik hiervoor geschorst worden?
Check je school regelboek.

## Misc.
#### Blijft het profiel administrator?
Ja.

#### Kan je het profiel niet meer administrator maken, of verwijderen?
Als je het profiel niet meer administrator wilt maken, moet je terug gaan in herstelmodus en command prompt openen. Voer dan deze commands uit.

Als je het profiel wilt verwijderen: `net user username /delete`, waarbij `username` de naam van het profiel is.
Als je de administrator wilt weghalen: `net localgroup administrators username /delete`, waarbij `username` de naam van het profiel is.
