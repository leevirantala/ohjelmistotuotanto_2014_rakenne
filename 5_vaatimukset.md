## Vaatimukset 
1. Toiminnalliset vaatimukset.

Ohjelmisto sisältää kolme-alasivua, joista yksi on aina auki.

Sivun yläosassa on jokaisella näistä sivuista samanlainen neli-paikkainen valikko, josta haluttua sivua painamalla voidaan siirtyä kyseiselle sivulle. Valikko pysyy aina näkyvillä. Sivut ovat: Jono&ruoka, Live, Vapaat paikat ja Sulje.

Applikaation käynnistyessä oletussivuna ensimmäisenä aukeaa Jono&ruoka-sivu. Sivu on kevyt, ja sisältää ruokalistan sekä jonon arvioidun pituuden tekstimuodossa. Sivu sovittuu käytettävän laitteen näytön mukaisesti, jotta vältetään turha selailu. Kevyt ja hyödyllinen sivu ensimmäiseksi, jotta latausajat pysyvät minimissä.

Yläpalkissa seuraava sivu on Live. Palkkia painettaessa siirrytään kyseiselle sivulle, josta on mahdollista tarkastaa ruokalan tilanne live-kuvasta. Live-kuva tulee sovitettuna laitteen näyttöön, ylä-palkin pysyessä näkyvissä kuvan yläpuolella.

Kolmas sivu on Vapaat paikat, jossa ohjelma ilmoittaa vapaiden istumapaikkojen sekä pöytien määrän selkeästi tekstimuodossa. Sisältää myös palkin nimeltä “tarkista live-kuvasta”, josta painamalla avataan live-kuva ruokalan pöydistä. Myös tämä kuva sovittuu laitteen näyttöön, avautuen palkin päälle, tekstien alle.

Neljäs ja viimeinen on sulje, josta painamalla applikaatio suljetaan, ja ohjelman käyttämä välimuisti vapautetaan.

2. Ei-toiminnalliset vaatimukset.

Sivujen vaatimat tiedot tulevat omalta serveriltä (live-kuvat, ruokalista, jonon ja paikkojen määrä). Tietomäärät eivät ole suuria, koska live-kuvaakaan ei ole tarvetta säilyttää. Kuitenkin live-kuvan lähetystä voidaan vaatia jopa pariin sataan laitteeseen kerrallaan, joten servereitä metropolian verkossa voidaan vaatia useampia.

Sivujen ja videon sovittamiseksi näytön mukaisiksi käytetään jQueryä ja css3:a.

Vapaiden paikkojen määrä perustuu käyttäjien gps-sijaintiin jota serveri vertaa ruokalan paikkamääriin. Palvelu ottaa huomioon, että todennäköisesti kaikilla ruokailijoilla ei ole applikaatiota ja lisää ihmisten lukumäärään 20%. Omaa tarkistamista varten live-kuvaa.

Mahdolliset järjestelmävirheet ovat todennäköisesti seurausta yhteysvirheistä. Virheiden ilmaantuessa annetaan ilmoitus: "possible connection problems, check connection and restart application". Koska applikaatio on kevyt, uudelleenkäynnistys ei vaadi aikaa eikä vaivaa.

3. Vaatimukset käyttäjältä.

Applikaation käyttö vaatii itse applikaation lisäksi vain internet-yhteyden, jonka latausnopeus riittää livekuvan vastaanottamiseen. Lisäksi GPS-tiedot vaaditaan. Metropolian toimipisteissä on opiskelijoille sekä henkilökunnalle oma WiFi-yhteys, jonka nopeus riittää palvelun käyttämiseen.

Applikaatio tukee kaikkia suurimpia nykykäyttöjärjestelmiä (Android, Windows Phone, iOS).
Laitteelta vaaditaan 5Mt vapaata muistia, johon applikaatio asennetaan. Keskusmuistia on oltava 4Mt, jotta vältetään ohjelman “lagisuus”.
Applikaatio on kevyt, eikä siis vaadi mobiililaitteelta juuri minkäänlaisia prosessointitehoja.
