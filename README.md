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
