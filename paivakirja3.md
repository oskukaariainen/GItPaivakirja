# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Jos tulee tehtyä paljon virheitä, tai alkaa kaduttaa, voi palata aiempaan versioon. Haaroja hyödyntämällä voi pelottomasti kokeilla uusia ideoita rikkomatta projektia. Jos idea toimii, sen voi lisätä kätevästi projektiin. Muutokset näkee selvästi sekä committien asianmukaisista viesteistä käy ilmi, mitä on viimeeksi itse tehnyt/ajatellut.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Jokainen saa oman haaransa, jossa työskennellä rauhassa; kaikki ei muokkaa samaa koodia samaan aikaan. Samaan projekttin voidaan samaan aikaan tehdä eri toiminallisuuksia. Kun yksittäisen kehittäjän sen hetkinen työ on valmis, hän voi yhdistää sen yhteiseen kehityshaaraan, jolloin mahdolliset ristiriidat muun koodin kanssa tulevat näkyviin ja ne voidaan ratkoa. Usean kehittäjän projektissa commit -viestit ovat vielä tärkeämpiä kuin sooloprojektissa. Niistä muut kehittäjät saavat käsityksen projektin vaiheista. Niiden täytyy aika tarkasti kuvata tehtyjä muutoksia.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Projektissa on ainakin kaksi haaraa: main ja develop. Omat työt tehdään ja talletetaan develop -haaraan. Ei koskaan suoraan main -haaraan.

Committien tulisi olla järkevän kokoisia ja niiden viesit järkevän pituisia sekä commitia kuvaavia. Ennen julkaisua (push) haetaan muiden mahdolliset koodit (pull) ja ratkotaan ristiriidat, jos/kun niitä on. Varmistettava, että koodi toimii.

Ennen työn aloittamista tarkistettava, ovatko muut tehneet muutoksia ja hakea ne itselleen (pull).

 Kun saadaan toimiva tuotos, lisätään kaikki mainiin.




__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Ilmeisen tärkeä osa ohjelmistokehitystä tämä kurssi. Materiaali tuntui kattavalta alkusysäykseltä. Kaikkea en millään pysty muistaa, mutta kertausta varmasti tulee työelämässä aikanaan. Työmäärä täydellinen. Joistain kohdsta olisin mielelläni katsonut viedon, missä näytetään ja selitetään vaihe kerrallaan.