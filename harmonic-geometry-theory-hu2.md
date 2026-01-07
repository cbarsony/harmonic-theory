# A harmonikus észlelés geometriai információelmélete

**Bársony Csaba**

**Egységes matematikai keretrendszer a zenei struktúrák érzelmi minőségeinek előrejelzésére**

---

## Absztrakt

Egy új elméleti keretrendszert mutatunk be, amely az emberi harmóniaérzékelést háromdimenziós geometriai térként modellezi, alapelvekből levezetve. Arra a megfigyelésre építve, hogy a hallgatók konzisztens érzelmi válaszokat mutatnak a skálákra, móduszokra és akkordokra, azt javasoljuk, hogy ezek a válaszok matematikailag megjósolhatók három független tengely mentén: **Fényesség** (klaszterezési pozíció az alaphanghoz képest), **Egyensúly** (hézagvariancia) és **Komplexitás** (intervallum-diverzitás).

Keretrendszerünk központi eleme a *Piszoár-elv* — egy minimális-hézag korlát, amely meghatározza azokat a határokat, amelyeken belül a zeneileg hasznos struktúrák léteznek. Kritikus fontosságú, hogy megmutatjuk: az egyenletesség maximalizálása (a korlát tökéletes teljesítése) nulla információtartalmú struktúrákat eredményez. A valódi optimalizálási cél a *komplexitás*: az aszimmetria, amely szemantikai jelentést hordoz. Továbbá azt javasoljuk, hogy a zenei struktúrák információhordozó jelekként működnek, ahol az egyenletes intervallum-mintázatoktól való eltérések alkotják a hallgatók által észlelt szemantikai tartalmat.

Ez a keretrendszer évszázadnyi zeneelméleti hagyományt redukál geometriai és információelméleti primitívekre, lehetővé téve a harmonikus „érzet" számítógépes elemzését és előrejelzését kulturálisan specifikus konvenciókra való hivatkozás nélkül.

**Kulcsszavak:** zenei megismerés, harmónia, információelmélet, geometriai zeneelmélet, intervallum-eloszlás, diatonikus skála, akkordérzékelés

---

## 1. Bevezetés

### 1.1 A zenei affektus problémája

Miért hangzik egy moll akkord „szomorúan" és egy dúr akkord „vidáman"? Miért éreznek egyes skálák „sötétnek", míg mások „fényesnek"? A hagyományos zeneelmélet leíró taxonómiákat kínál (dúr/moll, konszonáns/disszonáns), de ritkán nyújt matematikai elvekre alapozott *magyarázó mechanizmusokat*.

Azt állítjuk, hogy ezek az affektív minőségek a hangok geometriai eloszlásából erednek a 12 fokú egyenletes temperálású rendszeren belül, és hogy a hallgatók tudat alatt értékelik ezt az eloszlást több független tengely mentén.

### 1.2 A 12 hangos axióma

Keretrendszerünk egy alapvető egyszerűsítésen nyugszik:

> **Minden zene 12 félhangon belüli mintázatokra redukálható.**

Az oktáv-ekvivalencia miatt — az a pszichoakusztikai jelenség, ahol az oktávnyi távolságra lévő hangmagasságokat alapvetően „ugyanannak" érzékeljük — minden harmonikus kapcsolatot egy 12 elemből álló körkörös tér pozícióiként modellezhetünk (a *hangnem-kör*).

Ez a nyugati zene „assembly nyelve": az az irreducibilis szubsztrátum, amelyre minden harmónia, dallam és skálaszerkezet épül.

### 1.3 Előzmények

A zeneelmélet geometriai megközelítéseinek előzményei vannak Tymoczko (2011) szólamvezetési geometriáról és Callender és mtsai. (2008) általánosított szólamvezetési terekről szóló munkáiban. Hozzájárulásunk abban különbözik, hogy az *észlelési dimenziókra* összpontosít a transzformációs kapcsolatok helyett, és explicit módon összekapcsolja a geometriai tulajdonságokat az információelméleti mértékekkel.

---

## 2. A Piszoár-elv

### 2.1 A minimális hézag mint korlát

Tekintsük a következő heurisztikát, amelyet *Piszoár-elvnek* nevezünk:

> **Adott n pozíció kitöltése 12 méretű térben, az elhelyezésnek ki kell elégítenie egy minimális elfogadható távolságot bármely két szomszédos pozíció között.**

Ez az elv — amely analóg a személyes tér fenntartásának szociális viselkedésével — egy *korlátot* határoz meg, nem egy *optimalizálási célt*. Kritikus fontosságú, hogy az egyenletesség maximalizálása nulla információtartalmú struktúrákhoz vezet (lásd §4). A tritónusz (1,7) tökéletesen egyenletes, de zeneileg instabil; a bővített hármashangzat (1,5,9) tökéletesen kiegyensúlyozott, de „lebegő" és ritkán használják nyugvópontként.

**A korlát-optimalizálás megkülönböztetés:** A piszoár-elv egy *padlót* határoz meg (ne legyenek túl kicsi hézagok), míg az információtartalom (Z-tengely) adja az *optimalizálási célt*. A zeneileg hasznos struktúrák kielégítik a minimális-hézag korlátot, miközben *aszimmetriát vezetnek be* a szemantikai tartalom hordozására.

### 2.2 Alkalmazás a diatonikus skálára

A diatonikus skála 7 hangot tartalmaz 12 félhangon elosztva. Intervallum-mintázata:

$$[2, 2, 1, 2, 2, 2, 1]$$

Ez *majdnem* 7 elem legegyenletesebb eloszlása 12 pozícióban — de kritikus fontosságú, hogy nem tökéletesen egyenletes. Egy 7 hangú egészhangú részskála egyenletesebb lenne, de elveszítene egy hangot. A diatonikus skála két félhangja (1-esek) a lehető legtávolabb helyezkedik el egymástól (2 és 3 egészhang választja el őket), kielégítve a piszoár-korlátot, miközben *pontosan annyi aszimmetriát* vezet be, amennyi az információtartalom létrehozásához szükséges.

**1. tétel:** *A diatonikus skála az egyetlen 7 hangú skála, amely kielégíti a minimális-hézag korlátot (nincs hézag < 1), miközben pontosan 2 intervallumtípust tart fenn, ezáltal maximalizálva a komplexitást (Z) a korláton belül.*

Ez magyarázza, miért dominál a diatonikus skála az egészhangú skála felett: mindkettő kielégíti a hézag-korlátot, de a diatonikus Z ≈ 0,86, míg az egészhangú Z = 0.

### 2.3 Alkalmazás az akkordépítésre

Az akkordépítés ugyanezt az elvet követi. Adott egy hármashangzat (3 hang 12 pozícióban):

| Akkord | Hézagok | Min hézag | Z (Komplexitás) |
|--------|---------|-----------|-----------------|
| Dúr (1,5,8) | 4, 3, 5 | 3 | 1,0 |
| Moll (1,4,8) | 3, 4, 5 | 3 | 1,0 |
| Szűkített (1,4,7) | 3, 3, 6 | 3 | 0,92 |
| Bővített (1,5,9) | 4, 4, 4 | 4 | **0** |

A bővített hármashangzat tökéletes egyenletességet ér el (minden hézag egyenlő), de *nulla információt* hordoz — nincsenek különböző megfordításai és „lebegőnek" vagy „iránytalannak" hangzik. A dúr és moll hármashangzatok feláldoznak némi egyensúlyt a komplexitásért: egyenlőtlen hézagaik (3 különböző érték) létrehozzák a jelentést kódoló aszimmetriát. Ezért alapvetőek a dúr/moll hármashangzatok, míg a bővített hármashangzatok átmenetiek.

---

## 3. A háromdimenziós harmonikus tér

Azt javasoljuk, hogy az észlelt harmonikus minőség leképezhető egy háromdimenziós térre, amelyet független geometriai és információelméleti mértékek határoznak meg.

### 3.1 X tengely: Fényesség (klaszterezési pozíció)

**Definíció:** A fényesség az intervallum-klaszterezés pozícióját méri a kijelölt alaphanghoz képest.

A diatonikus skála móduszaira:

| Módusz | Mintázat | Első intervallumok | Fényesség |
|--------|----------|-------------------|-----------|
| Lokriszi | F-E-E-F-E-E-E | F, E | Legsötétebb (−3) |
| Fríg | F-E-E-E-F-E-E | F, E | Nagyon sötét (−2) |
| Eol | E-F-E-E-F-E-E | E, F | Sötét (−1) |
| Dór | E-F-E-E-E-F-E | E, F | Semleges (0) |
| Mixolíd | E-E-F-E-E-F-E | E, E | Semleges+ (0) |
| Ión | E-E-F-E-E-E-F | E, E | Fényes (+1) |
| Líd | E-E-E-F-E-E-F | E, E, E | Legfényesebb (+2) |

**Elv:** Az alaphang közelében lévő félhangok észlelési „feszültséget" vagy „sötétséget" hoznak létre. Az alaphang közelében lévő egészhangok „nyitottságot" vagy „fényességet" teremtenek.

**Képlet (egyszerűsített):**
$$X = \sum_{i=1}^{n} w_i \cdot I_i$$

ahol $I_i$ az $i$-edik pozícióban lévő intervallum az alaphangtól, és $w_i$ egy súlyozási függvény, amely csökken az alaphangtól való távolsággal.

### 3.2 Y tengely: Egyensúly (hézagvariancia)

**Definíció:** Az egyensúly az intervallum-eloszlás egyenletességét méri, a pozíciótól függetlenül.

**Képlet:**
$$Y = 1 - \text{Var}(G)$$

ahol $G = [g_1, g_2, ..., g_n]$ a szomszédos hangok közötti ciklikus hézagok vektora.

| Struktúra | Hézagok | Variancia | Egyensúly |
|-----------|---------|-----------|-----------|
| Bővített (1,5,9) | 4,4,4 | 0,00 | Maximum |
| Szűk7 (1,4,7,10) | 3,3,3,3 | 0,00 | Maximum |
| Dom7 (1,5,8,11) | 4,3,3,2 | 0,50 | Magas |
| Dúr (1,5,8) | 4,3,5 | 0,67 | Magas |
| Add2 (1,3,5,8) | 2,2,3,5 | 1,50 | Közepes |
| Klaszter (1,2,3) | 1,1,10 | 18,0 | Minimum |

**Értelmezés:** A magas egyensúlyú akkordok „teljesnek" vagy „stabilnak" érzékelődnek. Az alacsony egyensúlyú akkordok „dőlőnek" vagy „feloldatlannak" érzékelődnek.

### 3.3 Z tengely: Komplexitás (intervallum-diverzitás)

**Definíció:** A komplexitás az intervallum-mintázat információtartalmát méri, amelyet a különböző intervallumtípusok számaként vagy a hézagsorozat entrópiájaként fogalmazunk meg.

**Képlet (entrópia-alapú):**
$$Z = -\sum_{k} p_k \log_2 p_k$$

ahol $p_k$ a $k$ méretű hézagok aránya.

| Struktúra | Hézagok | Különböző típusok | Entrópia | Komplexitás |
|-----------|---------|-------------------|----------|-------------|
| Egészhangú | 2,2,2,2,2,2 | 1 | 0,00 | Minimum |
| Diatonikus | 2,2,1,2,2,2,1 | 2 | 0,86 | Optimális |
| Harmonikus moll | 2,1,2,2,1,3,1 | 3 | 1,38 | Magas |
| Kromatikus | 1,1,1,1,1,1,1,1,1,1,1,1 | 1 | 0,00 | Nulla (zaj) |

---

## 4. Az információelméleti értelmezés

### 4.1 A zene mint modulált jel

Egy alapvető újraértelmezést javasolunk:

> **A zenei struktúrák információhordozó jelekként működnek. A „vivőhullám" az egyenletes intervallum-eloszlás; a „moduláció" az egyenletességtől való eltérés.**

Tekintsük az akusztikus hullámformákkal való analógiát:

| Tartomány | Egyenletes (nincs információ) | Modulált (információ) |
|-----------|------------------------------|----------------------|
| Hang | Tiszta szinuszhullám | Komplex hullámforma felharmonikusokkal |
| Hangszín | Hangvilla | Hegedű, gitár, énekhang |
| Skálák | Egészhangú (2-2-2-2-2-2) | Diatonikus (2-2-1-2-2-2-1) |
| Akkordok | Bővített (4-4-4) | Dúr (4-3-5), Moll (3-4-5) |

### 4.2 A szabálytalanságok mint szemantikai tartalom

A diatonikus skála félhangjai nem „hibák" — ezek alkotják az *információtartalmat*. Nélkülük a skála az egészhangú skálába omlik össze, amely:

- Nincsenek különböző móduszai (1 egyedi rotáció)
- Nem ad „otthon" vagy „feloldás" érzést
- Univerzálisan „lebegőnek" vagy „iránytalannak" írják le

A diatonikus skála két félhangja úgy működik, mint az alapfrekvenciához hozzáadott felharmonikusok: gazdagságot, karaktert és jelentést hoznak létre.

### 4.3 Az Aranyhaj-zóna

A zenei hasznosság a komplexitás egy korlátozott tartományában létezik:

$$0 < Z < Z_{max}$$

| Komplexitás | Példa | Észlelés |
|-------------|-------|----------|
| Z ≈ 0 | Egészhangú, kromatikus | Unalmas / Zaj |
| Z ≈ 0,5 | Blues skála, bebop kiegészítések | Feszültség, rejtélyes, „kereső" |
| Z ≈ 1 | Diatonikus | Optimális gazdagság |
| Z ≈ 1,5 | Harmonikus moll | Egzotikus, „fűszeres" |
| Z > 2 | Véletlenszerű intervallumok | Kaotikus, feldolgozhatatlan |

Ez párhuzamos az információelmélettel: a nulla entrópiájú jel nem hordoz információt; a maximális entrópiájú jel megkülönböztethetetlen a zajtól.

**A harmonikus analógia:** A hullám-metaforát kiterjesztve, a Z-tengelyt úgy érthetjük meg, mint ami a zenei struktúra „felharmonikus tartalmát" írja le:

| Zóna | Hullám-analógia | Észlelési minőség |
|------|-----------------|-------------------|
| Z ≈ 0,5 | Alaphang gyenge felharmonikussal | Vékony, teljességre vágyó |
| Z ≈ 1 | Alaphang kiegyensúlyozott felharmonikusokkal | Teljes, kielégítő |
| Z ≈ 1,5 | Alaphang extra felharmonikusokkal | Gazdag, majdnem túlzó |

**A Feszültség-zóna (Z ≈ 0,5):** A Z ≈ 0,5 értékű struktúrák „majdnem egyenletesek, egy figyelemre méltó kivétellel" — mint egy tiszta hang egyetlen halvány felhanggal. Ez a *hiányosság* érzetét kelti: a fül észleli a struktúrát, de többet akar. Ez a jazz átmenő hangok, blues „blue note"-ok és filmscore-ambiguitás harmonikus tere. A „feloldott" helyett „érdekes" hangzásokat kereső zeneszerzők gyakran ebben a zónában dolgoznak.

**A Telítettség-zóna (Z ≈ 1,5):** Fordítva, a Z > 1 struktúrák „extra" intervallumtípusokat tartalmaznak — mint egy felharmonikusokkal túlterhelt alaphang. A fül a gazdagságot a túlzás határán érzékeli: egzotikus, fűszeres, majdnem túl sok információ. A harmonikus moll bővített szekundja a klasszikus példa — egy harmadik intervallumtípust (3) ad hozzá, amely megkülönböztető „keleti" vagy „spanyol" színt teremt.

---

## 5. Empirikus előrejelzések

Keretrendszerünk tesztelhető előrejelzéseket generál:

### 5.1 Első előrejelzés: A móduszok fényességi sorrendje

A hét diatonikus módusszal szembesülő hallgatók konzisztensen a következő sorrendbe rangsorolják „fényességüket" vagy „boldogságukat":

$$\text{Lokriszi} < \text{Fríg} < \text{Eol} < \text{Dór} < \text{Mixolíd} < \text{Ión} < \text{Líd}$$

Ez a sorrend közvetlenül következik a félhangok alaphanghoz viszonyított pozíciójából.

### 5.2 Második előrejelzés: Akkordstabilitás értékelések

A hallgatók akkord „stabilitás" vagy „teljesség" értékelései fordítottan korrelálnak a hézagvarianciával:

$$r(\text{Stabilitás}, Y) > 0,7$$

### 5.3 Harmadik előrejelzés: Optimális négyeshangzat-választás

Adott egy dúr hármashangzat {1, 5, 8}, a hallgatók azokat a bővítéseket preferálják, amelyek minimalizálják a hézagvarianciát:

| Bővítés | Eredmény | Hézagok | Variancia | Előrejelzett preferencia |
|---------|----------|---------|-----------|--------------------------|
| +9 (poz 11) | 1,5,8,11 | 4,3,3,2 | 0,50 | Magas |
| +6 (poz 10) | 1,5,8,10 | 4,3,2,3 | 0,50 | Magas |
| +2 (poz 3) | 1,3,5,8 | 2,2,3,5 | 1,50 | Közepes |
| +4 (poz 6) | 1,5,6,8 | 4,1,2,5 | 2,50 | Alacsony (sérti a min-hézagot) |

### 5.4 Negyedik előrejelzés: Skálapreferencia

Amikor új skálák létrehozására kérik, a zeneszerzők olyan eloszlások felé konvergálnak, amelyek:
1. **Kielégítik** a minimális hézag korlátot (piszoár-elv — nincs túl kicsi hézag)
2. **Maximalizálják** a komplexitást 2-3 különböző intervallumtípus fenntartásával (információtartalom)
3. **Fenntartanak** ésszerű egyensúlyt (kerülik a szélsőséges varianciát)

Figyeljük meg a sorrendet: a piszoár-elv egy *kielégítendő korlát*, nem egy *maximalizálandó cél*. Az egyenletesség maximalizálása egészhangú skálákat eredményez (Z = 0); a komplexitás maximalizálása a korláton belül diatonikus struktúrákat eredményez (Z ≈ 1).

---

## 6. Az egységes modell

### 6.1 A háromdimenziós harmonikus tér

```
                              Z+ : KOMPLEX (gazdag)
                              ▲   Harmonikus moll (telített)
                              │
                              │   Diatonikus (optimális)
                              │
                              │   Blues, Bebop (vékony, vágyakozó)
                              │
    X− : SÖTÉT ◄──────────────┼──────────────► X+ : FÉNYES
    (Lokriszi, Fríg)          │                (Líd, Ión)
                              │
                              ▼
                              Z− : EGYSZERŰ (unalmas)
                              Egészhangú, Szűk7, Bőv


           Y− : KIEGYENSÚLYOZATLAN ◄──┼──► Y+ : KIEGYENSÚLYOZOTT
           (dőlő, klaszterek)         │    (egyenletesen elosztott)
                                      │
              Add2, Sus4              │    Bővített, Szűk7
              (instabil)              │    (stabil de unalmas)
```

### 6.2 Formalizáció

Bármely hangnem-halmazra $S = \{s_1, s_2, ..., s_n\}$ kijelölt alaphanggal $s_1$:

1. **Hézagok számítása:** $G = [g_1, g_2, ..., g_n]$ ahol $g_i = (s_{i+1} - s_i) \mod 12$

2. **Fényesség (X):** 
$$X(S) = \sum_{i=1}^{k} \alpha^{i-1} \cdot g_i$$
ahol $\alpha < 1$ a korai intervallumokat súlyozza erősebben.

3. **Egyensúly (Y):**
$$Y(S) = \frac{1}{1 + \text{Var}(G)}$$

4. **Komplexitás (Z):**
$$Z(S) = H(G) = -\sum_{v \in \text{unique}(G)} \frac{c_v}{n} \log_2 \frac{c_v}{n}$$
ahol $c_v$ a $v$ hézagérték előfordulása.

### 6.3 Az észlelési optimum

A leggyakrabban használt zenei struktúrák egy specifikus régióban csoportosulnak:

| Struktúra | X | Y | Z |
|-----------|---|---|---|
| Ión módusz | +1 | Magas | 0,86 |
| Eol módusz | −1 | Magas | 0,86 |
| Dúr hármashangzat | +1 | Magas | 1,0 |
| Moll hármashangzat | −1 | Magas | 1,0 |
| Dom7 | +0,5 | Magas | 1,0 |
| Pentatonikus | 0 | Magas | 0,97 |

Ezek a struktúrák közösek: **mérsékelt fényesség, magas egyensúly és mérsékelt komplexitás.**

---

## 7. Diszkusszió

### 7.1 A hagyományos szabályok magyarázata

Keretrendszerünk magyarázatokat ad a hagyományosan „axiomatikus" szabályokra:

| Hagyományos szabály | Geometriai magyarázat |
|---------------------|----------------------|
| „Kerüld a párhuzamos kvinteket" | Hézagvariancia-ugrásokat hoz létre a szólamvezetésben |
| „Oldd fel a tritónuszt" | A tritónusz maximális helyi feszültséget teremt (hézag-aszimmetria) |
| „A szeptimakkordok lefelé oldódnak" | Helyreállítja az egyensúlyt a legkisebb hézag eliminálásával |
| „A sus4 helyettesíti a tercet" | Együttes létezésük sérti a min-hézag korlátot |

### 7.2 A lokriszi speciális esete

A lokriszi univerzálisan kerülendő a tonális zenében. Keretrendszerünk megmagyarázza, miért:

1. **Legsötétebb módusz** (X = minimum): Félhang közvetlenül az alaphang felett
2. **Hiányzó P5**: Az ötödik fok szűkített (6 félhang, nem 7)

A tiszta kvint fontossága nem magyarázható egyedül a piszoár-elvvel — a tritónusz (6 félhang) „optimálisabb" lenne puszta távolság-maximalizálás szempontjából. Ehelyett a P5 elsőbbsége az *információelméletből* ered: az (1,8) kettőshang hézagai [7,5], ami Z = 1,0-t ad, míg a tritónusz (1,7) hézagai [6,6], ami Z = 0-t ad. A P5 kielégíti a hézag-korlátot *és* információt hordoz; a tritónusz jobban kielégíti, de semmit nem hordoz.

A lokriszi szűkített kvintje így kudarcot vall a Z-tengelyen: egy információhordozó intervallumot szimmetrikussra cserél, destabilizálva a módusz szemantikai tartalmát.

### 7.3 Kulturális univerzalitás vs. specifikusság

Keretrendszerünk bizonyos kultúraközi univerzálékat jósol:
- Kiegyensúlyozott eloszlások preferenciája (magas Y)
- Mérsékelt komplexitás preferencia (középső Z)
- Alaphang-relatív feszültség észlelés (X tengely)

A kulturális variáció a következőkön keresztül lép be:
- Az X tengely preferált régiója (sötét vs. fényes esztétika)
- Tolerancia az alacsonyabb Y-ra (a „feloldatlan" struktúrák elfogadása)
- Komplexitás preferenciák (Z tartomány)

---

## 8. Implikációk a zenetechnológia számára

### 8.1 Automatizált kompozícióelemzés

Bármely zenei passzázs elemezhető az (X, Y, Z) trajektóriák időbeli kiszámításával, feltárva:
- Érzelmi ív (X mozgás)
- Feszültség/feloldás mintázatok (Y mozgás)
- Komplexitás moduláció (Z mozgás)

### 8.2 Generatív zenei rendszerek

A kompozíciós algoritmusok az (X, Y, Z) tér specifikus régióit célozhatják meg a kívánt érzelmi minőségek eléréséhez szabályalapú heurisztikákra való támaszkodás nélkül.

### 8.3 Zenei oktatás

A keretrendszer egységes magyarázatot ad arra, „miért" léteznek a hagyományos szabályok, a memorizálást megértéssel helyettesítve.

---

## 9. Általánosítás N-TET-re és folytonos hangtérre

### 9.1 A 12 fokú egyenletes temperáláson túl

Keretrendszerünk, bár 12-TET-tel mutatjuk be, természetesen általánosítható bármely egyenletes temperálású rendszerre. A 12-es szám bármely pozitív egész $N$-nel helyettesíthető, harmonikus terek családját eredményezve.

| Rendszer | N | Osztók | Kulturális kontextus |
|----------|---|--------|---------------------|
| 12-TET | 12 | 2,3,4,6 | Nyugati standard |
| 24-TET | 24 | 2,3,4,6,8,12 | Arab makám, török makam |
| 19-TET | 19 | prím | Kísérleti (jobb nagy tercek) |
| 31-TET | 31 | prím | Reneszánsz érdeklődés, kiváló kvintek és tercek |
| 53-TET | 53 | prím | Török elmélet, közel tökéletes tiszta hangolás közelítés |

Az általánosított képletek:

$$G(S) = [(s_2 - s_1), (s_3 - s_2), ..., (s_1 + N - s_n)]$$

$$\bar{g} = \frac{N}{n}$$

**Kulcsfontosságú felismerés:** A három tengely (X, Y, Z) bármely N-re érvényes marad. A *geometria* invariáns — csak a *felbontás* változik.

### 9.2 Az N észlelési korlátai

Létezik egy pszichoakusztikai plafon az értelmes felosztásra:

| Mérték | Érték | Implikáció |
|--------|-------|------------|
| **Éppen észrevehető különbség (JND)** | ~5-10 cent | Laborkörülmények, képzett hallgatók |
| **Zenei kontextus JND** | ~15-25 cent | Valós hallgatási körülmények |
| **Kategorikus észlelési határ** | ~50 cent | „Ugyanaz a hang" vs „különböző hang" |

Átszámítva N-TET lépésméretekre:

| Rendszer | Lépésméret | Észlelhető? | Megkülönböztethető kontextusban? |
|----------|------------|-------------|----------------------------------|
| 12-TET | 100 cent | ✓ Könnyen | ✓ Könnyen |
| 24-TET | 50 cent | ✓ Igen | ✓ Igen, gyakorlással |
| 48-TET | 25 cent | ✓ Alig | ⚠ Nehéz |
| 96-TET | 12,5 cent | ⚠ JND határán | ✗ Nem megbízhatóan |
| 200-TET | 6 cent | ✗ JND alatt | ✗ Nem |

**Gyakorlati plafon:** Körülbelül 50-100 felosztás, ahol a lépésméret megközelíti a JND küszöböt.

### 9.3 A folytonos határeset

Ahogy $N \to \infty$, a diszkrét hangnem-kör $\mathbb{Z}_N$ **folytonos körré** $S^1$ válik:

- **Hangnem** = szög $\theta \in [0, 2\pi)$
- **Hézag** = ívhossz a szomszédos hangok között
- **Egyensúly (Y)** = ívhosszak varianciája
- **Komplexitás (Z)** = hézag-eloszlás differenciális entrópiája

Azonban a folytonosságnak van észlelési korlátja. Az effektív maximum:

$$N_{észlelési} \approx \frac{1200 \text{ cent}}{JND} \approx 100-200$$

Ezen túl a felosztások észlelésileg egyenértékűvé válnak.

### 9.4 Miért optimális a 12

A 12-TET nem az észlelési optimum — hanem a **komplexitás-hasznosság optimum**, amely több versengő tényezőt egyensúlyoz:

| Tényező | Optimális N | Miért |
|---------|-------------|-------|
| **Észlelési felbontás** | ~100-200 | Megkülönböztethető hangmagasságok maximalizálása |
| **Tiszta hangolás közelítése** | 31 vagy 53 | Jobb tiszta kvintek és tercek |
| **Oszthatóság (szimmetria)** | 12, 24, 36 | Sok osztó lehetővé teszi a szimmetrikus jelzőpontokat |
| **Kognitív terhelés** | 5-12 | Emberi munkamemória ≈ 7±2 elem |
| **Hangszer-gyakorlatiasság** | 12-19 | Érintők, billentyűk, lyukak |
| **Notáció egyszerűsége** | 7-12 | Írható, olvasható |

**A 12 varázsa:** Ott helyezkedik el, ahol ezek a görbék optimálisan találkoznak:

1. **Elég felbontás** az expresszív zenéhez (Z > 0)
2. **Elég egyszerűség** a megismeréshez és hangszerekhez
3. **Gazdag oszthatóság** szimmetrikus struktúrákhoz (bővített, szűkített, tritónusz, egészhangú)
4. **Ésszerű tiszta hangolás közelítés** (P5 = 700¢ vs tiszta 702¢ = 2¢ hiba)

### 9.5 Az oszthatóság szerepe

Az oszthatóság lehetővé teszi a szimmetrikus felosztást, ami elengedhetetlen a hierarchikus struktúrák építéséhez:

| N | Osztók | Lehetővé tett szimmetrikus struktúrák |
|---|--------|--------------------------------------|
| 12 | 1,2,3,4,6,12 | Tritónusz (6), szűk7 (3), bőv (4), egészhangú (6) |
| 24 | 1,2,3,4,6,8,12,24 | Mind a fenti + negyedhang semlegesek |
| 19 | 1,19 (prím) | Nincs tökéletes szimmetrikus felosztás |
| 31 | 1,31 (prím) | Aszimmetriára kényszerít → természetesen magas Z |

**Hipotézis:** A kultúrák gazdag oszthatóságú N értékeket választottak, hogy szimmetrikus „nulla-információ" struktúrákat hozzanak létre referenciapontként, amelyekkel szemben az aszimmetrikus (információhordozó) struktúrák kontrasztot alkotnak.

### 9.6 24-TET: Megéri?

Igen, bizonyíthatóan. Az arab makám és török makam rendszerek értelmes módon használják a negyedhangokat:

| Makám | Megkülönböztető intervallum | Hatás |
|-------|----------------------------|-------|
| Raszt | „semleges terc" (~350 cent) | Se nem dúr, se nem moll |
| Bajáti | ~150 centes szekund | Jellegzetes „közel-keleti" szín |
| Szaba | Több semleges intervallum | Melankolikus, komplex |

Ezek az intervallumok *észlelésileg különbözőek* és *szemantikai tartalmat* hordoznak (magas Z), amelyet a 12-TET nem tud kifejezni.

### 9.7 Konklúzió: A 12 mint Nash-egyensúly

> **A 12 a zenei rendszerek Nash-egyensúlya.** Egyetlen változtatás sem javít egyszerre minden tényezőn.

A keretrendszer N-agnosztikus — bármely egyenletes temperálásra működik. A kulturális „N-választások" az oszthatóságra optimalizálhatnak, lehetővé téve a szimmetrikus jelzőpontokat, amelyekhez képest az értelmes aszimmetria mérhető.

---

## 10. Időbeli dinamika és akkumulált észlelés

### 10.1 A negyedik dimenzió: Idő

A három tengely (X, Y, Z) a hangnem-halmazok **statikus geometriai tulajdonságait** írja le — hol klasztereznek az intervallumok, mennyire egyenletesen oszlanak el, és mennyi információt hordoznak. De a zene időben bontakozik ki, és az időnek van egy mély tulajdonsága: **egyirányú**.

Ennek az egyirányúságnak mély következményei vannak a harmonikus észlelésre.

### 10.2 Az akkumulatív észlelés elve

Hallgatás közben minden hang *megmarad* a hallgató emlékezetében egy ideig. Új hangok hallásakor az agy *kombinálja* őket a nemrég hallott hangokkal, egy **virtuális hangnem-halmazt** konstruálva, amely csak az észlelésben létezik. Egy egyszólamú dallam akkorddá vagy skálává válik *a hallgató elméjében*.

> **A zene nem harmonikus állapotok sorozata — hanem egy út a harmonikus téren keresztül, amelyet az akkumulált észlelés vés ki.**

Tekintsünk egy egyszerű dallamsorozatot:

| Idő | Hallott hang | Akkumulált halmaz | Emergáló struktúra |
|-----|--------------|-------------------|-------------------|
| T₀ | C | {C} | Egyetlen hang |
| T₁ | E | {C, E} | Nagyterc |
| T₂ | G | {C, E, G} | Dúr hármashangzat megjelenik |
| T₃ | H | {C, E, G, H} | Dúr7 akkord |
| T₄ | D | {C, D, E, G, H} | Bővített hangzás |

A hallgató nem „akkordot" hall — hanem egy dallamot, amely **implikál** egy akkordot az időbeli akkumuláción keresztül.

### 10.3 Az időbeli akkumuláció tulajdonságai

| Tulajdonság | Leírás | Zenei következmény |
|-------------|--------|-------------------|
| **Egyirányú** | A hangok nem „hallhatók vissza" — a kontextus csak növekszik | A múlt formálja a jelent; nincs menekülés a kialakult kontextusból |
| **Lecsengő** | A régebbi hangok elhalványulnak a munkamemóriából | A friss hangok dominálnak; a távoli hangok „háttérré" válnak |
| **Aszimmetrikus** | A sorrend számít: C→E→G ≠ G→E→C | Ugyanaz a hanghalmaz, különböző érzelmi trajektória |
| **Emergáló** | A harmónia szekvenciális bemenetből kristályosodik | A dallam és a harmónia észlelésileg egyesül |

### 10.4 Matematikai formalizáció

A statikus hangnem-halmaz $S$ időfüggő **akkumulált virtuális halmazzá** $S(t)$ válik:

$$S(t) = \sum_{\tau=0}^{t} w(t-\tau) \cdot n_\tau$$

ahol:
- $n_\tau$ = a $\tau$ időpontban hallott hangnem
- $w(t-\tau)$ = lecsengési súlyfüggvény (mennyire erősen „emlékszünk" a $(t-\tau)$ időegységgel ezelőtt hallott hangokra)
- $S(t)$ = az akkumulált virtuális hanghalmaz $t$ időpontban

A $w$ lecsengési függvény valószínűleg exponenciális vagy hatványtörvény formát követ:

$$w(\Delta t) = e^{-\lambda \Delta t}$$

ahol $\lambda$ egy lecsengési állandó, amely a zenei tempóhoz és a kognitív feldolgozási sebességhez kapcsolódik.

### 10.5 Dinamikus koordináták

Az időfüggő akkumulációval a háromdimenziós koordinátáink **trajektóriákká** válnak:

$$X(t) = X(S(t)), \quad Y(t) = Y(S(t)), \quad Z(t) = Z(S(t))$$

Egy zenemű többé nem egy pont az (X, Y, Z) térben — hanem egy **út** azon a téren keresztül, amelyet a hallgató akkumulálódó észlelése nyom.

```
                    Z (Komplexitás)
                    ▲
                    │      ╭──→ Kibontakozás
                    │     ╱
                    │    ●  Csúcspont
                    │   ╱
                    │  ╱
                    │ ● ← Nyitás (ritka)
                    │╱
    X (Fényesség) ──┼─────────────────→
                   ╱│
                  ╱ │
                 ╱  │
                ╱   │
               Y (Egyensúly)
```

### 10.6 Magyarázó erő

Ez az időbeli keretrendszer olyan jelenségeket magyaráz, amelyeket a statikus elemzés nem tud:

| Jelenség | Magyarázat az akkumuláción keresztül |
|----------|--------------------------------------|
| **A dallam harmóniát implikál** | Az akkumulált hangok virtuális akkordokat alkotnak a memóriában |
| **Az első benyomások számítanak** | Tabula rasa → az első hangok alapkontextust hoznak létre |
| **Az ismétlés stabilitást teremt** | Az ismételt hangok megerősítik az akkumulált halmaz súlyait |
| **A „rossz" hangok lehetnek „helyesek"** | A feloldódó disszonancia hozzájárul a konszonáns akkumulált halmazhoz |
| **Csúcspont és feloldás** | A trajektória eléri a magas-Z régiót, majd leereszkedik |
| **A moduláció mozgásnak érződik** | Az út áthalad a harmonikus tér új régiójába |

### 10.7 A zeneszerző feladatának újraértelmezése

> **A kompozíció az (X, Y, Z) téren keresztül vezető út megtervezésének művészete, amelyet a hallgató az akkumulált észlelésen keresztül fog bejárni.**

A zeneszerző nem statikus akkordokat helyez el — hanem hangokat szekventál, tudva, hogy a hallgatók *akkumulálni* fogják őket emergáló harmonikus struktúrákká. A képesség abban rejlik, hogy megjósolja és formálja ezt az akkumulációt.

---

## 11. Konklúzió

Egy geometriai keretrendszert mutattunk be a harmonikus észlelés megértéséhez, most már négy dimenzióra kiterjesztve:

1. **A Piszoár-elv** egy *korlátot* határoz meg (minimális elfogadható hézag), nem optimalizálási célt
2. **Fényesség (X)** megragadja a sötét-fényes érzelmi gradációt a klaszterezési pozíción keresztül
3. **Egyensúly (Y)** megragadja a stabilitást a hézagvariancián keresztül
4. **Komplexitás (Z)** megragadja a gazdagságot az intervallum-diverzitáson keresztül — és ez az *elsődleges optimalizálási cél*
5. **Idő (T)** bevezeti az akkumulált észlelést — a hangok kombinálódnak a memóriában, a statikus koordinátákat dinamikus trajektóriákká alakítva a harmonikus téren keresztül

Döntő fontosságú, hogy a zenei struktúrákat **információhordozó jelekként** értelmezzük újra, ahol az intervallum-mintázatok szabálytalanságai alkotják a hallgatók által észlelt szemantikai tartalmat. A tökéletes szimmetria (tritónusz, bővített hármashangzat, egészhangú skála) maximálisan kielégíti a piszoár-korlátot, de nulla információt hordoz. A diatonikus skála elterjedtsége nem önkényes — a zenei információ optimális kódolását képviseli: elég aszimmetrikus a jelentéshez, elég kiegyensúlyozott a koherenciához, az elfogadható hézag-eloszlás korlátain belül.

Az időbeli dimenzió felfedi, hogy a zene nem harmonikus állapotok sorozata, hanem egy **út a harmonikus téren keresztül**, amelyet a hallgató akkumulált észlelése vés ki. Ez az egyirányú akkumuláció magyarázza, miért implikál a dallam harmóniát, miért horgonyozzák le az első benyomások az észlelést, és miért a kompozíció alapvetően a trajektória-tervezés művészete.

Ez a keretrendszer a zeneelmélet leíró komplexitását geometriai és információelméleti primitívekre redukálja, mind magyarázó erőt, mind számítási kezelhetőséget kínálva.

---

## Hivatkozások

Callender, C., Quinn, I., & Tymoczko, D. (2008). Generalized voice-leading spaces. *Science*, 320(5874), 346-348.

Tymoczko, D. (2011). *A Geometry of Music: Harmony and Counterpoint in the Extended Common Practice*. Oxford University Press.

Shannon, C. E. (1948). A mathematical theory of communication. *Bell System Technical Journal*, 27(3), 379-423.

Clough, J., & Douthett, J. (1991). Maximally even sets. *Journal of Music Theory*, 35(1/2), 93-173.

---

## A. függelék: Akkord- és skálakoordináták

### A.1 Gyakori akkordok

| Akkord | Fokok | X (Fényes) | Y (Egyensúly) | Z (Komplex) |
|--------|-------|------------|---------------|-------------|
| Dúr | 1,5,8 | +2 | 0,60 | 1,00 |
| Moll | 1,4,8 | −2 | 0,60 | 1,00 |
| Szűkített | 1,4,7 | −3 | 0,33 | 0,92 |
| Bővített | 1,5,9 | +1 | 1,00 | 0,00 |
| Sus4 | 1,6,8 | 0 | 0,33 | 0,92 |
| Maj7 | 1,5,8,12 | +2 | 0,40 | 1,00 |
| Dom7 | 1,5,8,11 | +1 | 0,67 | 1,00 |
| Min7 | 1,4,8,11 | −1 | 0,67 | 1,00 |
| Szűk7 | 1,4,7,10 | −3 | 1,00 | 0,00 |
| Maj6 | 1,5,8,10 | +2 | 0,67 | 1,00 |
| Min6 | 1,4,8,10 | −1 | 0,67 | 1,00 |

### A.2 Gyakori skálák

| Skála | Intervallumok | X (Fényes) | Y (Egyensúly) | Z (Komplex) |
|-------|---------------|------------|---------------|-------------|
| Ión | 2,2,1,2,2,2,1 | +2 | 0,81 | 0,86 |
| Dór | 2,1,2,2,2,1,2 | 0 | 0,81 | 0,86 |
| Fríg | 1,2,2,2,1,2,2 | −3 | 0,81 | 0,86 |
| Líd | 2,2,2,1,2,2,1 | +3 | 0,81 | 0,86 |
| Mixolíd | 2,2,1,2,2,1,2 | +1 | 0,81 | 0,86 |
| Eol | 2,1,2,2,1,2,2 | −2 | 0,81 | 0,86 |
| Lokriszi | 1,2,2,1,2,2,2 | −4 | 0,81 | 0,86 |
| Harmonikus moll | 2,1,2,2,1,3,1 | −2 | 0,64 | 1,38 |
| Melodikus moll | 2,1,2,2,2,2,1 | −1 | 0,81 | 0,86 |
| Egészhangú | 2,2,2,2,2,2 | 0 | 1,00 | 0,00 |
| Pentatonikus dúr | 2,2,3,2,3 | +1 | 0,80 | 0,97 |

---

## B. függelék: Matematikai definíciók

### B.1 Ciklikus hézagvektor

Hangnem-halmazra $S = \{s_1, s_2, ..., s_n\}$ hangmagasság szerint rendezve:

$$G(S) = [(s_2 - s_1), (s_3 - s_2), ..., (s_1 + 12 - s_n)]$$

### B.2 Hézagvariancia

$$\text{Var}(G) = \frac{1}{n}\sum_{i=1}^{n}(g_i - \bar{g})^2$$

ahol $\bar{g} = \frac{12}{n}$ (az átlagos hézag n hangra 12 félhangban).

### B.3 Hézagentrópia

$$H(G) = -\sum_{v \in V} p_v \log_2 p_v$$

ahol $V$ az egyedi hézagértékek halmaza és $p_v = \frac{|\{g_i : g_i = v\}|}{n}$.

---

*Kézirat elkészítve: 2026. január*

**Bársony Csaba**
