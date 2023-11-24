## Legaliteit
#### Is dit legaal?
nee! misschien kan het hun regels breken met de mensen waarbij ze de laptops lenen, maar je kan geen straftijd krijgen

#### Kan ik hiervoor geschorst worden?
dat is echt een jouw probleem, ga door je schoolregels heen lezen

## Misc.
#### Blijft het profiel administrator?
ya totdat de ICT de laptop opnieuw verziekt of je hem zelf verwijdert/van administrator afhaalt

#### Kan je het profiel niet meer administrator maken, of verwijderen?
ya, als je zo'n profiel hebt gemaakt. ga in herstelmodus en naar command prompt en voer deze commands uit.

als je het profiel wilt verwijderen: `net user username /delete`, waarbij `username` de naam van het profiel is
als je de administrator wilt weghalen: `net localgroup administrators username /delete`, waarbij `username` de naam van het profiel is


# De rest hier is best oud en ik ga het niet meer updaten.
## Errors
#### De computer start na de restart weer op in herstelmodus!
Dit kan gebeuren, en het is makkelijk oplosbaar. Druk op Windows Toets en R tegelijk, en typ dan `msconfig`. Druk op OK, en ga naar het tabblad `Computer opstarten`. Onderaan zie je dan "Opstarten in veilige modus". Zet dit uit, en herstart de computer.

#### Ik krijg een "toegang geweigerd" error in herstelmodus!
Dit betekent dat je school de herstelmodus in Netwerk modus heeft gezet.  Druk op Windows Toets en R tegelijk, en typ dan `msconfig`. Druk op OK, en ga naar het tabblad `Computer opstarten`. Onderaan zie je dan "Opstarten in veilige modus". Zet dit als het nog niet aan staat aan, zet dan Minimaal aan. Herstart nu de computer.
