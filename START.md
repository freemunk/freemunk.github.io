## Herstelmodus opstarten

Om deze exploit uit te voeren, moeten we herstelmodus opstarten. Hierin zijn alle restricties en profielen uitgeschakeld, waardoor we via Command Prompt wat code kunnen uitvoeren en een nieuwe gebruiker aanmaken die administratieve toegang heeft.

Eerst gaan we de makkelijkste manier proberen.

1. Druk op de Windows toets + I. 
*Als dit niet werkt, klik dan op het Windows icoon op je taakbalk en klik daarna op de Instellingen.*
*Als Instellingen uitgezet is op je laptop, [klik hier](METHODS.md) om alternatieve methoden te bekijken*
2. Selecteer op Windows 10 Bijwerken en Beveiliging, en op Windows 11 selecteer je Systeem.
3. Wanneer je in een van die menus zit, klik dan op Systeemherstel op het zijbalk van het Instellingen menu.
4. Klik onder het kopje Geavanceerd Opstarten op Nu opnieuw opstarten.
5. Je zal nu het winRE menu ingaan.

![winRE menu](https://support.content.office.net/nl-nl/media/85d63652-68b6-9a70-60e4-c63825eaca59.png)

## Administrator worden

We zullen nu in deze modus jouw Administrator maken.

1. Klik op de Windows toets en R tegelijk.
2. Typ `cmd` in.
3. Druk op `OK`
5. Typ nu, in het programma dat geopent is, `net localgroup administrators defaultuser0 /add` en druk op Enter.
6. Herstart de computer.

Als het goed gelukt is, is het profiel nu administrator. Log in op je account en doe wat je wilt!
Ben je bang dat de school je account kan tracken als je je eigen account gebruikt? Volg dan deze stappen om een nieuw profiel aan te maken.

1. Typ in het cmd programma `net user username password /add`, waarbij je `username` vervangt met het profiel z'n naam en `password` met het profiel z'n wachtwoord. Druk nu op enter.
2. Typ nu in `net localgroup administrators username /add`, waarbij je `username` vervangt met het naam van het profiel die je hebt gemaakt.
3. Log nu in op het nieuwe profiel met het wachtwoord dat je hebt gemaakt.

Gefeliciteerd! Je kan nu doen wat je wilt op de laptop. Ik ben niet verantwoordelijk voor wat je op de laptops doet.
