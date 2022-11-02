# sv-hallintasovellus (Kuvaus on raakile ja tarkentuu kun palaute on saatu)

Soitinvuokrien hallintasovellus (josta lyhenne SV). Sovelluksen aihe olisi siis hyvin spesifisti ratkaista ongelma, johon törmäsin opiskellessani Sibelius-akatemian lyömäsoitinluokalla. Luokan yksi tehtävistä on hallinnoida soitinvuokrapyyntöjä joita akatemia saa. Tämä tarkoittaa käytännössä sitä että yksi opiskelijoista tietää aina että, minne mitäkin soittimia on vuokrattu ja että riittävätkö soittimet yliopiston omiin projekteihin. Ongelmana on että vuokrien päällekkäisyyksiä on toisinaan hankala huomata ja ainoastaan vastuuopiskelijalla on tieto mitä soittimia on milloinkin vuokralla. Sovelluksen ajatus olisi siis, että ylläpitäjä pystyy luomaan uusia tapahtumia, joihin liitetään tietyt soittimet. Muut käyttäjät voivat katsoa tapahtumia, etsiä tiettynä ajanjaksona tapahtuvia tapahtumia ja esittää ylläpitäjälle ns tapahtumapyyntöjä. 

Olisi siis olemassa (ainakin) taulut:
Käyttäjät:
  Ylläpitäjä -> pystyy lisäämään/poistamaan tapahtumia ja katsella niitä
  Käyttäjä -> voi katsella tapahtumia ja lähettää tapahtumapyyntöjä ylläpitäjälle

Tapahtumat:
  Ajankohta
  Yhteyshenkilö
  Sijainti
  Yliopiston sisäinen/ulkopuolinen tapahtuma
  Soitinlista
  
Tapahtumapyynnöt:
  Sama kuin tapahtumat
  
Lisäksi voisi ehkä olla taulu soittimet. Tällöin sovellus voisi esimerkiksi varoittaa ylläpitäjää mahdollisista päälekkäisyyksistä. Tähän ehkä kaipaisin ohjaajalta vinkkiä että meneekö liian mutkikkaaksi kurssin tavoitteisiin nähden.
