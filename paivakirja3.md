# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Versionhallinnasta on hyötyä myös yksin työskennellässä. Sen avulla projektin kehityshistoria säilyy ja aiempiin versioihin on helppo palata. Se tekee myös kokeilemisesta turvallista, koska uusia ominaisuuksia voi testata erillisissä haaroissa ilman, että pääprojektin ominaisuudet tai koodi rikkoutuu. Lisäksi commit -viestien avulla on mahdollista pitää yksinkertaista dokumentaatiota projektista.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Useamman kehittäjän projektissa versionhallinta on lähes välttämätöntä. Sen avulla kaikki voivat keskittyä samanaikaisesti eri ominaisuuksien kehittämiseen ilman, että muutokset menevät sekaisin. Git myös ilmoittaa mahdollisista ristiriidoista, jolloin konfliktit voidaan ratkaista hallitusti. Versionhallinta myös tallentaa automaattisesti tiedon siitä, kuka on tehnyt mitäkin ja milloin. Pull requestin avulla muutokset voidaan tarkistaa ennen yhdistämistä, mikä parantaa ohjelmiston laatua ja helpottaa tiimityötä

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Projektitiimin versionhallinta kannattaa järjestää siten, että yksi tiimin jäsen luo GitHub-repositorion ja kutsuu muut jäsenet mukaan. Jokainen kloonaa repositorion omalle koneelleen ja päähaara pidetään aina toimivassa ja julkaistavassa kunnossa. Uudet ominaisuudet kehitetään aina omissa haaroissaan, jotka nimetään selkeästi niiden tarkoituksen mukaan. Muutosten jälkeen haarat pusketaan GitHubiin ja niistä tehdään pull request, jonka joku toinen tiimin jäsen tarkistaa ennen yhdistämistä päähaaraan. Tällä tavoin muutokset tulevat tarkastetuiksi ennen kuin ne otetaan käyttöön. Ennen uuden ominaisuuden aloittamista jokaisen tiimin jäsenen on hyvä päivittää paikallinen repositorio vastaamaan etärepositoriota, jotta mahdolliset ristiriidat vältetään. Kun ominaisuushaara on yhdistetty, se poistetaan sekä GitHubista että paikallisesti, jotta projektin rakenne pysyy siistinä ja hallittuna.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Kurssin materiaali oli kattava näkymä gitin perusominaisuuksista. Ennen kurssia olin käytännössä tehnyt ainoastaan push ja pull toimintoja omissa pienissä projekteissani.

Itse opin parhaiten tekemällä ja koin, että tehtävien määrä oli kohtuullinen, mutta riittävä kurssin laajuuteen nähden ja antoi minulle eväät viedä git-osaamistani pidemmälle.  