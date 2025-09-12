# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Viikon tehtävät ja materiaali auttoivat hahmottamaan etä- ja paikallisrepositorioiden suhdetta. Ymmärrän nyt, että paikallisrepot toimivat itsenäisesti ja niitä voi käyttää ilman etärepoa. Etärepo puolestaan mahdollistaa työn jakamisen muiden kanssa ja auttaa yhdistämään eri käyttäjien tekemät muutokset. Haasteena on edelleen hahmottaa, milloin käyttää mitäkin komentoa, sillä olen tottunut hyödyntämään lähinnä git push- ja git pull -komentoja. En ole aiemmin osallistunut yhteisprojekteihin, vaan git-kokemukseni on kertynyt ainoastaan omista projekteista, joissa olen ollut ainoa tekijä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote add origin (remote osoite) | Lisää uuden etärepositorion nimellä origin, jotta paikallinen repo voidaan yhdistää siihen |
| git branch -M main | Nimeää nykyisen haaran uudelleen mainiksi (pakottaa nimen vaihdon tarvittaessa) |
| git push -u origin main | Lähettää main-haaran etärepoon ja asettaa sen jäljityssuhteeseen, jotta jatkossa riittää pelkkä git push |
| git fetch origin | Hakee kaikki muutokset ja uudet haarat etäreposta ilman että yhdistää niitä paikallisiin haaroihin |
| git checkout origin/main | Siirtyy etärepon main-haaraan lukutilassa (detached HEAD) |
| git merge origin/main | Yhdistää etärepon main-haaran nykyiseen paikalliseen haaraan |