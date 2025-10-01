# git-oppimispaivakirja
Kurssi: Git-versionhallinta - SOF013AS2A-3001 </br>
Tekijä: Timo Parviainen

# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Minulla on jonkin verran aiempaa kokemusta git-versionhallinnasta, mutta en ole käyttänyt sitä lähes vuoteen, joten moni asia oli ehtinyt unohtua. Kurssin ensimmäiset tehtävät toimivat hyvänä kertauksena, vaikka osa niistä olikin jo ennestään tuttuja. Tehtävien tekeminen sujui ilman suurempia haasteita. Uutta minulle olivat komennot revert, reset ja restore.

Ainoa hankaluus oli löytää tämä päiväkirja kloonatusta repositoriosta. Paikallisen repositorion toiminta on minulle jo melko selkeä, mutta paikallisen ja etärepositorion välinen yhteys kaipaa vielä harjoittelua. Onneksi siitäkin selvisi Googlaamalla.

## Osiossa käyttämäni Git-komennot.

| Komento | Kuvaus |
| --------| ------ |
| git add .  | Lisää kaikki työhakemistossa olevat muutokset stagelle |
| git commit -m "Selitys" | Tallentaa stagelle lisätyt muutokset paikalliseen repositoryyn commit-viestin kanssa |
| git status | Näyttää työhakemiston ja staging-alueen tilan, mitkä tiedostot on muutettu, lisätty tai vielä lisäämättä |
| git log | Näyttää commit-historian, tekijät ja viestit aikajärjestyksessä |
| git rm test.txt | Poistaa tiedoston versionhallinnasta ja työhakemistosta |
| git reset | Peruuttaa lisäykset stagelta |
| git restore | Nollaa työtilassa tehdyt muutokset, joita ei löydy vielä versionhallinnasta |
| git checkout | Palauttaa tiedostoja tietystä commitista |
| git branch nimi1 | Luo uuden branchin nimeltä nimi1 |
| gi switch nimi1 | Vaihtaa branchiin nimi1 |
| git branch | Listaa kaikki olemassa olevat branchit ja näyttää mikä niistä on käytössä |
| git branch -r | Listaa kaikki olemassa olevat remote branchit |
| git merge nimi1 | Yhdistää branchin nimi1 nykyiseen branchiin |

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
