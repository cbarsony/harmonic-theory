# A harmonikus észlelés geometriai információelmélete

**Bársony Csaba**

**Egységes matematikai keretrendszer a zenei struktúrák érzelmi minőségeinek előrejelzésére**

---

## Absztrakt

Egy új elméleti keretrendszert mutatunk be, amely az emberi harmóniaérzékelést háromdimenziós geometriai térként modellezi, alapelvekből levezetve. Arra az megfigyelésre építve, hogy a hallgatók konzisztens érzelmi válaszokat mutatnak a skálákra, móduszokra és akkordokra, azt javasoljuk, hogy ezek a válaszok matematikailag megjósolhatók három független tengely mentén: **Fényesség** (klaszterezési pozíció a gyökhanghoz képest), **Egyensúly** (hézagvariancia) és **Komplexitás** (intervallum-diverzitás).

Keretrendszerünk központi eleme a *Piszoár-elv* — egy maximális eloszlási heurisztika, amely megmagyarázza a diatonikus skála elterjedtségét és az optimális akkordhangzások felépítését. Továbbá azt javasoljuk, hogy a zenei struktúrák információhordozó jelekként működnek, ahol az egyenletes intervallum-mintázatoktól való eltérések alkotják a hallgatók által észlelt szemantikai tartalmat.

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

### 2.1 A maximális eloszlás mint optimalizáció

Tekintsük a következő heurisztikát, amelyet *Piszoár-elvnek* nevezünk:

> **Adott n pozíció kitöltése 12 méretű térben, az optimális elhelyezés maximalizálja a minimális távolságot bármely két szomszédos pozíció között.**

Ez az elv — amely analóg a személyes tér maximalizálásának szociális viselkedésével — megmagyarázza, miért érzékelünk bizonyos skálákat és akkordokat „természetesebbnek" vagy „kellemesebbnek", mint másokat.

### 2.2 Alkalmazás a diatonikus skálára

A diatonikus skála 7 hangot tartalmaz 12 félhangon elosztva. Intervallum-mintázata:

$$[2, 2, 1, 2, 2, 2, 1]$$

Ez 7 elem *maximálisan egyenletes* eloszlása 12 pozícióban. Egyetlen másik 7 hangú skála sem ér el jobb hézag-egyenletességet. A két félhang (1-esek) a lehető legtávolabb helyezkednek el egymástól (2 és 3 egészhang választja el őket).

**1. tétel:** *A diatonikus skála az egyetlen 7 hangú skála, amely maximalizálja a minimális intervallumot, miközben pontosan 2 intervallumtípust tart fenn.*

### 2.3 Alkalmazás az akkordépítésre

Az akkordépítés ugyanezt az elvet követi. Adott egy hármashangzat (3 hang 12 pozícióban):

| Akkord | Hézagok | Min hézag |
|--------|---------|-----------|
| Dúr (0,4,7) | 4, 3, 5 | 3 |
| Moll (0,3,7) | 3, 4, 5 | 3 |
| Szűkített (0,3,6) | 3, 3, 6 | 3 |
| Bővített (0,4,8) | 4, 4, 4 | 4 |

A bővített hármashangzat tökéletes egyenletességet ér el (minden hézag egyenlő), míg a dúr és moll hármashangzatok közel optimális eloszlást érnek el.

---

## 3. A háromdimenziós harmonikus tér

Azt javasoljuk, hogy az észlelt harmonikus minőség leképezhető egy háromdimenziós térre, amelyet független geometriai és információelméleti mértékek határoznak meg.

### 3.1 X tengely: Fényesség (klaszterezési pozíció)

**Definíció:** A fényesség az intervallum-klaszterezés pozícióját méri a kijelölt gyökhanghoz képest.

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

**Elv:** A gyökhang közelében lévő félhangok észlelési „feszültséget" vagy „sötétséget" hoznak létre. A gyökhang közelében lévő egészhangok „nyitottságot" vagy „fényességet" teremtenek.

**Képlet (egyszerűsített):**
$$X = \sum_{i=1}^{n} w_i \cdot I_i$$

ahol $I_i$ az $i$-edik pozícióban lévő intervallum a gyökhangtól, és $w_i$ egy súlyozási függvény, amely csökken a gyökhangtól való távolsággal.

### 3.2 Y tengely: Egyensúly (hézagvariancia)

**Definíció:** Az egyensúly az intervallum-eloszlás egyenletességét méri, a pozíciótól függetlenül.

**Képlet:**
$$Y = 1 - \text{Var}(G)$$

ahol $G = [g_1, g_2, ..., g_n]$ a szomszédos hangok közötti ciklikus hézagok vektora.

| Struktúra | Hézagok | Variancia | Egyensúly |
|-----------|---------|-----------|-----------|
| Bővített (0,4,8) | 4,4,4 | 0,00 | Maximum |
| Szűk7 (0,3,6,9) | 3,3,3,3 | 0,00 | Maximum |
| Dom7 (0,4,7,10) | 4,3,3,2 | 0,50 | Magas |
| Dúr (0,4,7) | 4,3,5 | 0,67 | Magas |
| Add2 (0,2,4,7) | 2,2,3,5 | 1,50 | Közepes |
| Klaszter (0,1,2) | 1,1,10 | 18,0 | Minimum |

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
| Hangszín | Hangvilla | Hegedű, gitár, hang |
| Skálák | Egészhangú (2-2-2-2-2-2) | Diatonikus (2-2-1-2-2-2-1) |
| Akkordok | Bővített (4-4-4) | Dúr (4-3-5), Moll (3-4-5) |

### 4.2 A szabálytalanságok mint szemantikai tartalom

A diatonikus skála félhangjai nem „hibák" — ezek alkotják az *információtartalmat*. Nélkülük a skála az egészhangú skálába omlik össze, amely:

- Nincsenek különböző móduszai (1 egyedi forgatás)
- Nem ad „otthon" vagy „feloldás" érzést
- Univerzálisan „lebegőnek" vagy „iránytannak" írják le

A diatonikus skála két félhangja úgy működik, mint az alapfrekvenciához hozzáadott felharmonikusok: gazdagságot, karaktert és jelentést hoznak létre.

### 4.3 Az Aranyhajszál-zóna

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

**A Feszültség-zóna (Z ≈ 0,5):** Az Z ≈ 0,5 értékű struktúrák „majdnem egyenletesek, egy figyelemre méltó kivétellel" — mint egy tiszta hang egyetlen halvány felhangal. Ez a *hiányosság* érzetét kelti: a fül észleli a struktúrát, de többet akar. Ez a jazz átmenő hangok, blues „blue note"-ok és filmscore-ambiguitás harmonikus tere. A „feloldott" helyett „érdekes" hangzásokat kereső zeneszerzők gyakran ebben a zónában dolgoznak.

**A Telítettség-zóna (Z ≈ 1,5):** Fordítva, a Z > 1 struktúrák „extra" intervallumtípusokat tartalmaznak — mint egy felharmonikusokkal túlterhelt alaphang. A fül a gazdagságot a túlzás határán érzékeli: egzotikus, fűszeres, majdnem túl sok információ. A harmonikus moll bővített szekundja a klasszikus példa — egy harmadik intervallumtípust (3) ad hozzá, amely megkülönböztető „keleti" vagy „spanyol" színt teremt.

---

## 5. Empirikus előrejelzések

Keretrendszerünk tesztelhető előrejelzéseket generál:

### 5.1 Első előrejelzés: A móduszok fényességi sorrendje

A hét diatonikus módusszal szembesülő hallgatók konzisztensen a következő sorrendbe rangsorolják „fényességüket" vagy „boldogságukat":

$$\text{Lokriszi} < \text{Fríg} < \text{Eol} < \text{Dór} < \text{Mixolíd} < \text{Ión} < \text{Líd}$$

Ez a sorrend közvetlenül következik a félhangok gyökhanghoz viszonyított pozíciójából.

### 5.2 Második előrejelzés: Akkordstabilitás értékelések

A hallgatók akkord „stabilitás" vagy „teljesség" értékelései fordítottan korrelálnak a hézagvarianciával:

$$r(\text{Stabilitás}, Y) > 0,7$$

### 5.3 Harmadik előrejelzés: Optimális négyeshangzat-választás

Adott egy dúr hármashangzat {0, 4, 7}, a hallgatók azokat a bővítéseket preferálják, amelyek minimalizálják a hézagvarianciát:

| Bővítés | Eredmény | Hézagok | Variancia | Előrejelzett preferencia |
|---------|----------|---------|-----------|--------------------------|
| +9 (poz 10) | 0,4,7,10 | 4,3,3,2 | 0,50 | Magas |
| +6 (poz 9) | 0,4,7,9 | 4,3,2,3 | 0,50 | Magas |
| +2 (poz 2) | 0,2,4,7 | 2,2,3,5 | 1,50 | Közepes |
| +4 (poz 5) | 0,4,5,7 | 4,1,2,5 | 2,50 | Alacsony (sérti a min-hézag-ot) |

### 5.4 Negyedik előrejelzés: Skálapreferencia

Amikor új skálák létrehozására kérik, a zeneszerzők olyan eloszlások felé konvergálnak, amelyek:
1. Maximalizálják a minimális hézagot (piszoár-elv)
2. Minimalizálják a hézagvarianciát (egyensúly)
3. 2-3 különböző intervallumtípust tartanak fenn (optimális komplexitás)

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

Bármely hangnem-halmazra $S = \{s_1, s_2, ..., s_n\}$ kijelölt gyökhangal $s_1$:

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

Ezek a struktúrák osztoznak: **mérsékelt fényesség, magas egyensúly és mérsékelt komplexitás.**

---

## 7. Diszkusszió

### 7.1 A hagyományos szabályok magyarázata

Keretrendszerünk magyarázatokat ad a hagyományosan „axiomatikus" szabályokra:

| Hagyományos szabály | Geometriai magyarázat |
|---------------------|----------------------|
| „Kerüld a párhuzamos kvinteket" | Hézagvariancia-ugrásokat hoz létre a szólamvezetésben |
| „Oldd fel a tritónuszt" | A tritónusz maximális helyi feszültséget teremt (hézag-aszimmetria) |
| „A szeptimakkordok lefelé oldódnak" | Helyreállítja az egyensúlyt a legkisebb hézag eliminálásával |
| „A sus4 helyettesíti a tercet" | Együttes létezésük sérti a min-hézag-korlátot |

### 7.2 A lokriszi speciális esete

A lokriszi univerzálisan kerülendő a tonális zenében. Keretrendszerünk megmagyarázza, miért:

1. **Legsötétebb módusz** (X = minimum): Félhang közvetlenül a gyökhang felett
2. **Hiányzó P5**: Az ötödik fok szűkített (6 félhang, nem 7)

A tiszta kvint a második legfontosabb intervallum az uniszónó után (piszoár-elv szerint: 7 félhang ≈ 12 fele). Hiánya alapvetően destabilizálja a móduszt.

### 7.3 Kulturális univerzalitás vs. specifikusság

Keretrendszerünk bizonyos kultúraközi univerzálékat jósol:
- Kiegyensúlyozott eloszlások preferenciája (magas Y)
- Mérsékelt komplexitás preferencia (középső Z)
- Gyökhang-relatív feszültség észlelés (X tengely)

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

## 9. Konklúzió

Egy háromdimenziós geometriai keretrendszert mutattunk be a harmonikus észlelés megértéséhez:

1. **A Piszoár-elv** megmagyarázza az optimális hang-eloszlást
2. **Fényesség (X)** megragadja a sötét-fényes érzelmi gradációt a klaszterezési pozíción keresztül
3. **Egyensúly (Y)** megragadja a stabilitást a hézagvariancián keresztül
4. **Komplexitás (Z)** megragadja a gazdagságot az intervallum-diverzitáson keresztül

Döntő fontosságú, hogy a zenei struktúrákat **információhordozó jelekként** értelmezzük újra, ahol az intervallum-mintázatok szabálytalanságai alkotják a hallgatók által észlelt szemantikai tartalmat. A diatonikus skála elterjedtsége nem önkényes — a zenei információ optimális kódolását képviseli: elég kiegyensúlyozott a koherenciához, elég komplex a jelentéshez.

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

| Akkord | Félhangok | X (Fényes) | Y (Egyensúly) | Z (Komplex) |
|--------|-----------|------------|---------------|-------------|
| Dúr | 0,4,7 | +2 | 0,60 | 1,00 |
| Moll | 0,3,7 | −2 | 0,60 | 1,00 |
| Szűkített | 0,3,6 | −3 | 0,33 | 0,92 |
| Bővített | 0,4,8 | +1 | 1,00 | 0,00 |
| Sus4 | 0,5,7 | 0 | 0,33 | 0,92 |
| Maj7 | 0,4,7,11 | +2 | 0,40 | 1,00 |
| Dom7 | 0,4,7,10 | +1 | 0,67 | 1,00 |
| Min7 | 0,3,7,10 | −1 | 0,67 | 1,00 |
| Szűk7 | 0,3,6,9 | −3 | 1,00 | 0,00 |
| Maj6 | 0,4,7,9 | +2 | 0,67 | 1,00 |
| Min6 | 0,3,7,9 | −1 | 0,67 | 1,00 |

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
