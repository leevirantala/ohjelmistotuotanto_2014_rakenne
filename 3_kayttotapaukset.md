## Käyttötapaukset

Loppukäyttäjinä sovelluksella olisi ylläpito ja peruskäyttäjä.
Ylläpito pitäisi huolta, että sovelluksesta saatava tieto olisi ajantasalla ja peruskäyttäjällä olisi pelkät lukuoikeudet.
http://users.metropolia.fi/~tuukkaan/Ohjelmistotuotanto/kayttotapaukset.png

Käyttötapausskenaario 1 (suomenkielinen peruskäyttäjä):
  Käyttäjä avaa sovelluksen, sulkee (tai jättää huomiotta) kielivaihtoehto-kysymyksen ja näkee päivän ruokalistan sekä arvioidun jonotusajan. Ruoka vaikuttaa hyvältä eikä jonoakaan pitäisi olla. Käyttäjä sulkee sovelluksen.

Käyttötapausskenaario 2 (muunkielinen, skeptinen käyttäjä):
  Käyttäjä avaa sovelluksen, ei ymmärrä suomenkielistä ruokalistaa. Ohjelma kysyy haluaako hän kenties vaihtaa kielen ja hän valitsee englanninkielisen ohjelman. Applikaatio päivittää tekstin englanniksi. Käyttäjä näkee ruokavaihtoehdot ja jonon määrän, mutta haluaa kuitenkin tarkistaa tilanteen live-kamerasta. Hän tarkistaa kuvasta jonon ja päättää jättää ruokailun myöhempään ja sulkee applikaation.
  
Käyttötapausskenaario 3 (suomenkielinen peruskäyttäjä):
  Käyttäjä avaa sovelluksen, sulkee (tai jättää huomiotta) kielivaihtoehto-kysymyksen ja näkee päivän ruokalistan sekä arvioidun jonotusajan. Käyttäjä haluaa tietää mitä huomenna on ruokana. Hän avaa viikon ruokalista -sivun ja näkee listan. Käyttäjä sulkee sovelluksen.

Käyttötapausskenaario 4 (suomenkielinen peruskäyttäjä, virhe):
  Käyttäjä avaa sovelluksen, sulkee (tai jättää huomiotta) kielivaihtoehto-kysymyksen, mutta tietoja ei ole saatavilla, sen sijaan näyttöön tulee ilmoitus "possible connection failure, check connection and restart application". Käyttäjä sulkee sovelluksen, kytkee laitteensa verkon päälle ja käynnistää sovelluksen uudestaan. Ruoka vaikuttaa hyvältä eikä jonoakaan pitäisi olla. Käyttäjä sulkee sovelluksen.

* Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen
  * mallipohja: määritä alkutila (initial state), normaali kulku (normal flow), lopputila (end state)
  * kerro myös kuinka normaali kulku voi mennä pieleen sekä
  * mahdolliset vaihtoehtoiset kulut (alternate flow)
