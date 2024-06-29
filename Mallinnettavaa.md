Mallinnettavaa on paljon. Olen käyttänyt placeholderina sketchfabin sisältöä.
Alla olevat listat ei ole täydellisiä, vaan ns "ensimmäinen iteraatio" jolla saa jonkin verran sisältöä. Melkein jokaisesta vähänkin isommasta modelista hyvä olla myös lod-versiot.
## Tarvittavia modeleita
### Ympäristöön

1. **Kasvillisuus**: Puita, pensaita, kukkia, ruohikkoa, sammalta, sieniä.
2. **Luonnonelementit**: Kivet, kalliot, purot, järvet, joet.
3. **Eläimet**: Lintuja, jäniksiä, kettuja, peuroja, pieniä jyrsijöitä.
4. **Rakennukset**: Vanhoja mökkejä, hylättyjä taloja, latoja, navettoja.
5. **Ajoneuvot**: Ruostuneita autoja, polkupyöriä, veneitä.
6. **Tie- ja polkuvarusteet**: Aidat, portit, sillat, polut, opastekyltit.
7. **Roskat**: Muovipulloja, tölkkejä, paperiroskia, vanhoja lehtiä.

### Asunnoista

1. **Keittiö**
    - Astiat: lautaset, kupit, lasit, kattilat, pannut, Arabian astiastot, emalikupit.
    - Ruoat: säilykkeet, mausteet, kuivaruoka, hedelmät, vihannekset.
    - Välineet: veitsi, haarukka, lusikka, leikkuulauta, keittiöpyyhkeet.
    - Laitteet: jääkaappi, hella, mikroaaltouuni, kahvinkeitin, leivänpaahdin, puuhella, liesituuletin.
    - Perinneruoat: ruisleipä, karjalanpiirakat, hernekeitto, mämmi.
1. **Olohuone**
    - Huonekalut: sohva, nojatuolit, pöytä, kirjahylly, kaappi.
    - Elektroniikka: televisio, vanha radio. 
    - Kirjat ja lehdet: romaanit, aikakauslehdet, sanomalehdet.
    - Koristeet: valokuvat, taulut, kynttilät, koriste-esineet, suomalaiset taideteokset, Marimekon kankaat, Iittalan lasiesineet.
	- Perinteiset huonekalut: puusohva, räsymatot, keinutuoli.
    
1. **Makuuhuone**
    - Sänky: patjat, tyynyt, peitot, lakanat.
    - Yöpöytä: lamppu, herätyskello, kirjat.
    - Vaatteet: kaapit, hyllyt, vaatteet lattialla, vaatepinoja, villasukat, toppatakki, pipo.
    - Muut: peilit, matot, koriste-esineet, saunatakki, tikkataulu, seinävaate.
    
1. **Kylpyhuone**
    - Hygieniatuotteet: saippua, shampoo, hammastahna, hammasharja, Tervasaippua, Lumene-tuotteet.
    - Pyyhkeet: kylpypyyhkeet, käsipyyhkeet, pesulaput.
    - Muut: peilit, kaapit, lääkkeet, pesuaineet, roskakori, pyyhekoukut, pyykkikori.
	- Saunatarvikkeet: kiulu, vasta (tai vihta), laudeliinat.

2. **Varasto/työpaja**
    - Työkalut: vasarat, ruuvimeisselit, naulat, ruuvit, saha, kirves, moottorisaha, talikko.
    - Varusteet: työkalulaatikot, naulakot, tarvikekorit,  tynnyrit, öljykanisterit, katiska (kalastusväline).
    - Muut: puutavara, maalit, siveltimet, vanhat huonekalut.

1. **Yleiset**
    - Valaistus: lamput, kattovalaisimet, taskulamput.
    - Kodinkoneet: pesukone, kuivausrumpu, pölynimuri, astiankuivauskaappi, kaappipakastin.
    - Muut: talouspaperi, wc-paperi, muovipussit, kierrätyspaperi.
	- Valaistus: kynttilät, ulkotulet, vanhat öljylamput.

### Ulkoympäristö
1. **Luonto**    
    - Metsät: mäntymetsät, kuusimetsät, koivumetsät.
    - Vesistöt: järvet, lammet, joet, suot.
    - Kasvillisuus: mustikat, puolukat, suopursut, variksenmarjat, kanervat.
    - Eläimet: hirvet, sudet, karhut, metsot, joutsenet, ketut.
2. **Rakennukset ja Rakennelmat**
    - Mökit ja saunat: perinteiset hirsimökit, rantasaunat.
    - Piharakennukset: aitat, halkoliiterit, puuceet.
    - Vanhat maatalousrakennukset: navetat, heinäladot, vilja-aitat.
3. **Polut ja Tiet**
    - Metsäpolut, soratiet, asfalttitiet.
    - Maanviljelystiet: traktoriurat, peltojen väliset polut.
4. **Paikalliset Erikoisuudet**
    - Postilaatikot rivissä tien varrella.
    - Maitolaiturit.
    - Metsästys- ja kalastuspaikat: laavut, nuotiopaikat, pilkkireiät talvella.

### Paikalliset Yksityiskohdat
1. **Perinteet ja Kulttuuri**
    - Juhannus: juhannussalko, kokko.
    - Joulu: joulukuusi, tonttukoristeet, glögi, piparkakut.
    - Pääsiäinen: virpomisvitsat, mämmi.
2. **Arki ja Ympäristö**
    - Sienestys ja marjastus: sienikorit, marjasangot.
    - Kalastus: kalaverkot, onget, kalastusvälineet.
3. **Historialliset ja Kulttuurilliset Viittaukset**
    - Kansalliseepos: Kalevala-aiheiset esineet ja taideteokset.
    - Sotahistoria: vanhat kenttäpullot, aseet, uniformut.

Ja kuten listasta näkee, siitä puuttuu vielä _paljon_, mutta siltikin siinä on jo paljon tehtävää.

Alla hieman teknistä diipadaapaa
#### LOD (level of detail)
LOD on tekniikka jossa malli vaihdetaan toiseen etäisyyden mukaan. Mitä kauempana malli on, sitä karkeampi versio siitä esitetään. Suosittelen tekemään mallista ensin korkealaatuisen version ja sen jälkeen vähitellen poistaa siitä yksityiskohtia; joko käsin tai esimerkiksi Blenderin decimate-modifierin avulla. Koska tiedostot voi sisältää useamman meshin, meshit kannattaa nimetä tyyliin meshname_LODX, esimerkiksi sign_LOD2. Kun meshit on nimetty näin, Unity osaa suhteellisen helposti rakentaa näistä automaattisesti LOD-järjestelmän joka hieman helpottaa työskentelyä.
Joistakin malleista on hyvä luoda sprite viimeiseksi lod-malliksi. Näitä on esimeriksi puut, joita näkee kaukana horisontissa.

#### UV-mappaus
Modelit tosin tarvitsee myös tekstuureja. Ja jotta tekstuurit menee oikein, ne pitää uv-mapata.
UV-mappausta voi aika pitkälle tehdä automatisoidusti, mutta lähes poikkeuksetta käsin tehdyt mappaukset tuottaa paljon parempaa jälkeä.

#### Tekstuureista
Tekstuureja voi luoda esimerkiksi kolmella eri tavalla:
* Ota kuva jostain pinnasta, mahdollisimman neutraalit värit ja kuvan oltava kohtisuorassa, jotta jälkikäsittelyn projisointia olisi mahdollisimman vähän. Tämä kuva voi toimia joko suoraan tai referenssinä projektissa.
* Meshiä luodessa jokin sen pinta saattaa olla hyvinkin yksityiskohtainen. Tämä ei ole pelin kannalta välttämättä hyvä asia, jotenka pinta kannattaa leipoa (bake) tekstuuriksi. Hyvin yleinen käytäntö esimerkiksi normalmappien tekemiseen.
* Tekstuurin luominen sillä tarkoitetuilla ohjelmilla. Käytännössä mikä tahansa kuvankäsittelyohjelma sopii tähän, mutta on myös täysin tähän profiloituneita ohjelmia.

Tekstuurikokojen kanssa yleinen suositus on kahden potenssi, esimerkiksi 128x128, 256x256, 512x512 ... 4096x4096. Tekstuurikokoa kannattaa sovittaa hieman objektin kokoon ja miten olennaisesta objektista on kyse. Jokin antennin nuppi jossain talon katolla tuskin tarvitsee mitään 4k-tekstuuria, mutta jokin käsiase voi hyvinkin tarvita tarkan tekstuurin, koska sillä on mahdollisuus viedä iso osa ruudusta. Tällöin se kannattaa myös mallintaa varsin tarkasti.
Suosittelen tekemään ensin korkealaatuisen tekstuurin josta voi exportatessa downscaleta eri versiot, jotta löytyy se modeliin sopiva versio.
Ja koska tämä on yleensä ns. albedo-tekstuuri, eli se sisältää lähinnä väriarvot pinnalle, se ei riitä. Tarvitaan myös datatekstuurit, kuten normalmapit, specularmapit ja muut, jotta pinta vaikuttaa hyvältä. Yleinen käytäntö on, että ne on saman kokoisia albedon kanssa, mutta on myös poikkeuksiakin.

Vielä viimeiseksi tekstuureihin liittyen: tekstuureista voi luoda ns. atlaksen, joka on yksi isompi tekstuuri joka sisältää monta pienempää. Tämä on rendauksen kannalta kevyempää, koska ei tarvitse (välttämättä) vaihtaa jatkuvasti tekstuureja. Haittapuolena on, ettei näihin mahdu kovinkaan isoja tekstuureja ja ns. tilewrappaus (tekstuuri toistuu meshissä useaan otteeseen) ei onnistu ilman erillistä shaderia.

#### Materiaalit
Kun tekstuurit (color ja data) on olemassa, niistä voi luoda lopulta materiaalin, joka sitoo kaikki tarvittavat tekstuurit yhteen. Esimerkiksi jokin tiiliseinä voi sisältää kolme tai neljäkin eri tekstuuria. Materiaalille vielä hienosäädöt ja sen jälkeen sitä voi käyttää modelien kanssa.


### Riggaus ja animointi
Kun meshillä on tekstuurit, uv-mapit ja materiaalit, se mahdollisesti tarvitsee myös animaatioita.
Moni animaatio on toteutettu riggaamalla. Riggaamisessa on kyse siitä, että luodaan "luuranko" joka yleensä sijoitetaan meshin sisälle. Tämä luuranko ei ole semmoinen mikä rendataan pelissä. Luuranko koostuu luista. Jokainen luu sisältää painotuskartan meshin pintoihin liittyen. Eli paljonko kyseinen luu vaikuttaa tähän pintaan. Ja koska luut on yleensä hierarkisesti järjestetty, kaulassa olevan luun kääntäminen kääntää myös päätä. Kuten olkapään liikuttelu liikuttaa koko kättä.
Riggaus on varsin aikaavievää ja tarkkaa puuhaa. Blender onneksi osaa varsin hyvin luoda automatisoidun painotuskartan jokaiselle luulle. Toki tämän jälkeen ne on edelleen hyvä käydä läpi ja korjata mahdolliset virheet, mutta olen todennut että siltikin tämä on nopeampaa ja vähemmän rasittavaa kuin kaiken tekeminen täysin manuaalisesti.
Riggaamiseen liittyy vahvasti myös IK-järjestelmä, eli inverse kinematic. Tämä on tehty helpottamaan erityisesti mallintamista. Kuvitellaan vaikkapa kävelyanimaation tekemistä. Sen sijaan että liikutat ja käännät jokaista luuta erikseen keyframessa, liikutatkin vain yhtä, vaikkapa kantapäätä, ja jalka seuraa mukana varsin realistisesti. Näille voidaan laittaa erilaisia rajoituksia ja määrittelyjä, kuten paljonko kyseiset luut voi kääntyä, mihin suuntaan ja miten pitkälle ik-luu vaikuttaa. Eli jos kantapäässä olevaa ik-luuta nostaa, sen vaikutusalue loppuu lantioon.

Kun modelilla on luut, sille voidaan luoda animaatioita. Tapoja on käytännössä kaksi: mallinnusohjelmassa luotavat animaatiot, kuten kävely, hyppy, kyykistyminen, lataaminen, käsien käyttö, työntö, kuoleminen, pysähtyminen, paikoillaan olo, kääntyminen eri suuntiin, kävelyn aloittaminen, kävelyn lopettaminen jne. Toinen ryhmä on proseduraariset animaatiot, joita luodaan esimerkiksi koodilla. Pienet kameran heilumiset, tärinät tai muu pieni variointi. Yleensä näissä ohjataan ik-luita joita varsinaiset luut seuraa ja täten mesh seuraa luita.

Animaatioissa on myös eräs tärkeä vaihe, sillä niihin voi yleensä sijoittaa *eventtejä*. Event on jokin kohta animaatiossa jolloinka voidaan kutsua koodia. Hyöty on siinä, että voidaan luoda ääni alkamaan aina kun kenkä osuu maahan tai tietyssä kohtaa animaatiota alkaa tietty ääni ylipäätään tai animaation loppuessa vasta annetaan kontrolli takaisin pelaajalle.


#### Colliderit ja hitboxit
Lopuksi haluan tuoda esille colliderit ja hitboxit. Ensinnäkin, jokainen mesh ei tarvitse collideria/hitboxia. Tässä tapauksessa collider ja hitbox on samoja asioita. Kyse on komponenteista jotka määrittää mikä on este ja mikä ei. Tästä on myös advanced-versio jossa käytetään collider-matriisia. Tämä matriisi on kaksiuloitteinen taulukko, jossa voi määrittää mitkä groupit törmää keskenään ja mitkä ei. Esimerkiksi jokin lasipullo ja pelaaja ei törmää keskenään. Näitä ei kannata laskea. Mutta lasipullo ja ammus törmääkin ja aiheuttaa törmäyksen. Tämä sen takia, jotta törmäystarkistukset olisi kevyempiä käsitellä. Se on toki hieman vaivalloista käydä jokainen mesh näin läpi, mutta suorituskyvyn kannalta todella kannattavaa.
Suorituskyvystä tuli mieleen myös, että hitboxia luodessa, kannattaa suosia primitiivisiä muotoja meshien sijaan. Eli kuutiot, laatikot, pallot ja ympyrät todella hyviä juttuja. Mesh-collidereita kannattaa välttää, koska ne on raskaita laskea. Tai jos välttämättä pitää käyttää meshcollideria, silloin sille kannattaa tehdä erikseen oma mesh johon viitataan. Yksinkertaistettu mesh jälleen hyvä luoda Blenderin decimate-välineellä.


#### Lopuksi
Kuten yllä nähtiin, pelkästään mallintamiseen menee paljonkin aikaa. Toki niputin sen alle paljon muutakin kuin meshin luomisen. Valmis model on aikaavievä prosessi. Toki läheskään kaikki modelit ei tarvitse yllä olevia vaiheita ja jotkut niistä voi toteuttaa paljon kevyemmin. Jätin suosiolla tästä pois optimointimenetelmät joita voi editorissa hyödyntää, jotta joskus pääsen myös tekemään jotain muutakin kuin kirjoittamaan näistä tekstejä. :P
Sen haluisin vielä lisätä, että ei ole maailmanloppu jos alkuun meshit on vähän sinnepäin tai vaikka täysin placeholdereita joko liian isolla verteksimäärällä tai liian pienellä, animoinnit ei ole valmiita tai colliderit on miten sattuu ja lodit puuttuu. Kyse on iteroinnista, jossa vähitellen asiat valmistuu. Jos aina odottaa että modeli on täysin valmis ennen kuin siirtyy seuraavaan, joutuu siitä mahdollisesti muutkin odottaa.

