Baketus/bakeaminen/leipominen, tekniikka jossa pinnoista rendataan tekstuureita.
Tekniikka on varsin hyödyllinen jos meillä on ensin korkealaatuinen versio meshistä ja halutaan luoda verteksi/pintamäärältään pienempi versio.

Alla esimerkki kun tein sähkökaappia.
![[imgs/20240630020505.png]](imgs/20240630020505.png)
Ei mikään monimutkaisin objekti, mutta sen primitiivimuoto toimii hyvänä esimerkkinä.

- Kopioin kaapista kloonin ja laitoin alkuperäisen päälle. 
- Loin kaksi kuvaa: color ja normal. Molemmat 1024x1024 px.
- Loin myös kaksi materiaalia. Alkuperäinen sekä baked.
Alkuperäinen materiaali näyttää tältä:
![[20240630015146.png]](imgs/20240630015146.png)
Ei siis kovinkaan monimutkainen.
Baked-materiaali ei myöskään kovinkaan monimutkainen:
![[20240630015234.png]](imgs/20240630015234.png)
Nyt voimme leipoa tekstuurit. Otetaan ensin diffuse/albedo, eli perus väritekstuuri.
- Mene Blenderissä Render-välilehdelle
- Etsi Bake-osuus ja valitse Bake Type:ksi Diffuse.
- Laita päälle Selected to Active
- Valitse baked-materiaalista kumpaan kuvaan rendataan, tässä tapauksessa color.
- Collection-näkymästä valitse ensin se ns. heikkolaatuisempi versio ja viimeisenä parempilaatuinen versio meshistä. Lopuksi painaa Bake, ja tämä luo tekstuurin.
- Kun tekstuuri on luotu, paina uv-näkymässä shift+alt+s tallentaaksesi tekstuurin.
Normal-tekstuurin kanssa aikalailla sama homma.

Lopulta Unityssä molemmat vierekkäin:
![[20240630020505.png]](imgs/20240630020505.png)
