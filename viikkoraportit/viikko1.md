# viikkoraportti 1
Projektin tarkoituksena on rakentaa robotti, joka tunnistaa lähimpänä olevan kriteerit täyttävän esineen, jota se käy koskemassa. Robotti myös pysyy merkityllä alueella.

# sensorit
Robotti tarvitsee ultraäänisensorin löytääkseen kohteen suunnan ja etäisyyden. Kosketus tunnistetaan kosketussensorilla. Merkittyjen rajojen sisällä pysymistä valvotaan värisensorilla.


# rakenteesta

robotin pyöriä pyörittävät kaksi moottoria. Kääntyminen suoritetaan kääntämällä pyöriä eri suuntiin. Liikkumiseen tällä menetelmällä löytyy valmiit kirjastot LeOS API:sta. Moottorit ovat kiinni takapyörissä. Laitteen keula on tennispallon päällä. Näin

# toiminta

Aluksi robotti pyörähtää ympäri ja yrittää löytää koskettavan esineen. Koskemassa lähintä esinettä. Tämän jälkeen se etsii toisen esineen, jota se käy koskemassa. Jatkokehityksessä selvietään mahdollisuus että robotti pitäisi kirjaa kaikista koskemistaan esineistä.

# haasteita
NXJ Controlilla ei saa mitään dataa ulos Ultraäänisensorilta eikä äänisensorilta. Väri ja Kosketussensorin tilan saa luettua, mutta vain jos se on portissa 1.

# mitä seuraavaksi?
Seuraavaksi olisi tarkoitus toteuttaa robotin itsenäinen liikkuminen merkittyjen rajojen sisällä.
Lisäksi olisi tarkoitus selvittää miten robotin suunnan saa mitattua liikkeen aikana, jotta voidaan tallentaa kohteen suunta ja etäisyys. Jossei muuta, käännetään robottia aste kerrallaan ja tallennetaan mitä siinä suunnassa on. Tämä saattaa osoittautua hitaaksi keinoksi.
