# poliisi-data
Poliisin toimintakustannuksia koskevaa dataa TSV-muodossa: [tämän twiittiketjun](https://twitter.com/koponenhilden/status/1444722955481755652) tausta-aineisto.

* `Budjettikirjan_tiedot.tsv` sisältää valtiovarainministeriön [Valtion talousarvioesitykset](https://budjetti.vm.fi/) -sivustolta scrapatut poliisin toimintamenoja koskevat datat: toteutuma 2012–2020 vuosien 2014–2022 budjeteista sekä arvio 2021 ja ennuste 2022 vuoden 2022 budjetista. **Voi sisältää virheitä!** Aineiston oikeellisuus on tarkistettu vain niiltä osin kuin tietoja on käytetty grafiikoissa. Scrapauksen aikana on voinut tapahtua virheitä, joiden vuoksi osa muista tiedoista ei välttämättä ole oikein.
* `Kulurakenne.tsv` sisältää poliisin kulut osa-alueittain. Pääosa tiedoista on peräisin Antti Honkamaan artikkelista [Poliisi varoittaa resurssipulan vakavista seurauksista – ”Tämä on ongelma”](https://www.uusisuomi.fi/uutiset/us/0a3746d6-0143-4838-ac55-92d1c6e3f148?ref=ampparit:b60a) Uudessa Suomessa, lisäksi tietoja on täydennetty eri lähteistä.
* `Toimitilat.tsv` sisältää poliisin toteutuneita toimitilamenoja perustuen yllä olevaan `Kulurakenne.tsv` -aineistoon, Tutkihallintoa.fi -sivuston tietoihin, Senaatti-kiinteistöjen julkistamiin tietoihin ja sekalaisiin lähteisiin. Pitkän aikavälin tiekartan tiedot ovat peräisin eduskunnan hallintovaliokunnan muistiosta.

Aineistossa käyteyään desimaalierottimena **pilkkua** `,`
