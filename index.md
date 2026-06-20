---
theme: jekyll-theme-cayman
title: WTI Nyersolaj Határidős Árelemzés
---
Mini kutatás: WTI nyersolaj határidős árak

Ez a notebook a mappában található Crude Oil WTI Futures Historical Data.csv fájlt dolgozza fel. A cél hat érthető vizualizáció készítése, majd mindegyik alatt rövid, magyar nyelvű elemzés és következtetés.

1. grafikon – Záróár trendje
<img width="1084" height="487" alt="Abra1" src="https://github.com/user-attachments/assets/95c7cc43-f18c-42c2-95d2-168bbf53be9f" />
Elemzés és következtetés

Az első ábra azt mutatja, hogy a vizsgált, mintegy egy hónapos időszakban a WTI határidős záróára markáns csökkenő trendet követett. A sorozat a mintavételi ablak elején, 2026 május közepén még 108 USD/hordó körüli szinten zárt, majd fokozatosan, időnként rövid oldalazásokkal erodálódott. A csökkenés nem egyenletes volt: voltak napok, amikor az ár enyhén visszakapaszkodott, de a magasabb csúcsok és mélypontok is egyre alacsonyabbak lettek, ami klasszikus lefelé mutató piaci struktúrát jelez. A hónap második felében, különösen június közepén a zuhanás felgyorsult, és a záróár a 77 USD/hordó közelébe süllyedt. Ez a mintegy 30 százalékos relatív visszaesés arra utal, hogy a piac tartósan árazta be a gyengébb keresletet, geopolitikai bizonytalanságot vagy túlkínálatot. A trendvonal alatti kitöltés vizuálisan is erősíti a negatív irányt: a befektetők számára rövid távon a short irány volt az erősebb. Ugyanakkor a legutóbbi napok enyhe stabilizációja arra is figyelmeztet, hogy extrém esés után technikai korrekció vagy konszolidáció is bekövetkezhet. Összességében a záróár-idősor alapján a mini kutatás fő üzenete egyértelmű: a vizsgált időszakban a nyersolaj ára strukturálisan gyengült, és a piaci hangulat inkább óvatos, kockázatkerülő volt.

2. grafikon – Záróárak eloszlása
<img width="1085" height="487" alt="Abra2" src="https://github.com/user-attachments/assets/d545a112-f658-4202-97cb-4ab2958ac3ab" />
Elemzés és következtetés

A hisztogram megmutatja, hogy a záróárak nem egyetlen „tipikus” érték körül csoportosultak, hanem viszonylag széles sávban oszlottak el. A legtöbb megfigyelés a 85–100 USD/hordó közötti tartományban helyezkedik el, ami azt jelenti, hogy a vizsgált hónap nagy részében a piac még magasabb árszinten működött. Ugyanakkor az eloszlás jobb oldali farka rövidebb, míg az alsó tartomány felé több adatpont tolódott a periodus végén, amikor az árak gyorsan estek. Az átlag és a medián összehasonlítása fontos: ha az átlag magasabb marad a mediánnál, az arra utalhat, hogy néhány korai, magasabb ár „húzza felfelé” a központi tendenciát, miközben a frissebb adatok már alacsonyabb szinten vannak. A KDE-görbe domború formája azt sugallja, hogy nincs extrém kettős csúcs, de a balra tolódó tömeg a piaci gyengülés véglegesedését tükrözi. Statisztikai szempontból ez azt jelenti, hogy a kockázatkezelés során nem elég egyetlen várható értéket nézni: az ár jelentős valószínűséggel mozoghatott a teljes intervallumon belül. A következtetés tehát az, hogy bár a minta rövid, az eloszlás alapján a WTI ára ebben az időszakban instabilabb és széttartóbb volt, mint egy szűk, stabil sávban mozgó piacon.

3. grafikon – Napi kereskedési volumen 
<img width="1087" height="487" alt="Abra3" src="https://github.com/user-attachments/assets/2d1bb94e-f2d5-4fce-8c43-f339b3acf12c" />
Elemzés és következtetés

A volumen oszlopdiagramja azt mutatja, hogy a kereskedési aktivitás naponta erősen ingadozott, ami tipikus a határidős piacokon, ahol hírek, makrogazdasági adatok és technikai szintek egyszerre hatnak a résztvevőkre. A vizsgált időszakban több olyan nap is volt, amikor a forgalom jelentősen meghaladta a száz- vagy akár a háromszázezer szerződéses szintet, miközben más napokon alacsonyabb, akár néhány ezer szerződés körüli aktivitás figyelhető meg. A színezés – zöld emelkedő, piros eső napokra – segít észrevenni, hogy a nagy volumenű napok nem mindig esnek egybe egyetlen irányú ármozgással, de a legnagyobb forgalmú sessionök gyakran együtt járnak erősebb napi változással. Ez arra utal, hogy amikor a piac új információt áraz be, a likviditás is megugranhat, mert több szereplő egyszerre módosítja pozícióját. A volumen csúcsai különösen fontosak a trend értelmezéséhez: tartós árcsökkenés mellett magas forgalom gyakran megerősíti a irányt, mert nem csupán technikai korrekcióról van szó. Összefoglalva a volumen-analízis azt sugallja, hogy a WTI piac ebben a mintában aktív és reaktív volt; a döntéshozók számára a csendes, alacsony volumenű napok kevésbé informatívak, míg a kiemelkedő forgalmú napok kulcsfontosságúak a trend validálásához.

4. grafikon – Napi százalékos árváltozás
<img width="1087" height="487" alt="Abra4" src="https://github.com/user-attachments/assets/88a7270e-1785-4e2f-9d1f-9845cd94382e" />
Elemzés és következtetés

A napi százalékos változások oszlopdiagramja jól szemlélteti, hogy a WTI árfolyam nem simán csúszott lefelé, hanem heves, naponta változó ingadozásokkal reagált a piaci hírekre. A nulla vonal feletti zöld oszlopok a pozitív napokat, az alatta lévő piros oszlopok a vesztes sessionöket mutatják. A mintában több olyan nap is szerepel, amikor az ár több százalékkal zuhant egyetlen kereskedési napon, ami rövid távon jelentős kockázatot jelent a tőkeáttételes pozíciók számára. Ugyanakkor vannak enyhébb, pluszban záró napok is, amelyek rövid távú technikai emelkedéseket vagy profitrealizálást tükrözhetnek egy hosszabb eső trend közepette. Fontos megfigyelés, hogy a nagy negatív napok gyakran egymást követik vagy erős piaci hangulatot erősítenek, ami önfenntartó eső spirált indíthat el, amíg új fundamentum nem állítja meg a mozgást. A diagram alapján a volatilitás aszimmetrikus: a vesztes napok abszolút értéke időnként nagyobb, mint a nyereséges napoké, ami összhangban van a korábban látott lefelé mutató trenddel. Következtetésként elmondható, hogy a piac rövid távon „hangos” volt: a befektetőknek számítaniuk kellett éles napi kilengésekre, és a kockázatkezelés – stop szintek, pozícióméretezés – kulcsszerepet játszott ebben az időszakban.

5. grafikon – Napi ársáv (High − Low)
<img width="1084" height="487" alt="Abra5" src="https://github.com/user-attachments/assets/1884af65-dff4-4811-9e10-b8f8695bc919" />
Elemzés és következtetés

Az ötödik ábra a napi ársávot, vagyis a napi maximum és minimum közötti különbséget mutatja, amely a piaci volatilitás egyik legegyszerűbb, mégis informatív mérőszáma. A WTI adatsorban ez az érték naponta jelentősen változik: vannak viszonylag nyugodt sessionök, amikor az ár szűk sávban mozog, és vannak olyan napok, amikor a kereskedők széles intervallumon belül „harcolnak” az irányért. A szélesebb ársávú napok gyakran egybeesnek nagyobb piaci bizonytalansággal, hírérzékenységgel vagy likviditási stresszel, különösen amikor az ár gyors esésbe vagy emelkedésbe kapaszkodik. A grafikon segít megkülönböztetni a csendes konszolidációt azoktól a napoktól, amikor a piac túlreagál. A vizsgált időszakban több kiemelkedő csúcs is látható, ami arra utal, hogy a nyersolaj ára nemcsak irányban, hanem ingadozás mértékében is kiszámíthatatlanabb lett. Ez különösen fontos határidős kereskedők számára, mert a szélesebb napi sáv nagyobb margin követelményt és stop-kockázatot jelenthet. Összességében a napi ársáv elemzése megerősíti: a piac nem stabil, alacsony volatilitású környezetben működött, hanem időszakonként fokozott bizonytalanságot mutatott, amely összhangban van a lefelé mutató ártrenddel és a nagy volumenű napokkal.

6. grafikon – Nyitó és záró ár összehasonlítása
<img width="686" height="687" alt="Abra6" src="https://github.com/user-attachments/assets/60ce78a2-86ad-4f35-99fc-4076dbb653cd" />
Elemzés és következtetés

A hatodik, pontdiagram alapú ábra a nyitó és záró árak kapcsolatát vizsgálja. Az átló vonal azt jelenti, hogy az adott napon az árfolyam gyakorlatilag változatlan maradt; a pontok feletti elhelyezkedés emelkedő napot, alatti elhelyezkedés csökkenő napot sugall. A mintában több piros pont is az átló alatt helyezkedik el, ami összhangban van azzal, hogy a vizsgált időszak általános hangulata gyengébb volt, és sok sessionben a záró ár a nyitó alatt maradt. Ugyanakkor vannak zöld pontok is, amelyek azt mutatják, hogy még erős lefelé mutató trend mellett is előfordultak sikeres intraday emelkedések, jóllehet ezek gyakran nem fordították meg a nagyobb struktúrát. A pontok eloszlása azt is mutatja, hogy az árak idővel lejjebb tolódtak: a korábbi, magasabb nyitó-záró párok felső tartományban clusterelnek, míg a későbbi megfigyelések az alsó zónában sűrűsödnek. Ez vizuálisan is megerősíti a korábbi trend- és eloszlás-elemzések üzenetét. A scatter plot tehát nem csupán technikai érdekesség, hanem azt is jelzi, hogy a piac rövid távú visszapattanásai ellenére a záró értékek strukturálisan alacsonyabb szinten stabilizálódtak. A mini kutatás záró következtetése: a WTI határidős piac ebben a rövid mintában gyengélkedő, volatilis és aktívan kereskedett időszakot mutatott.

Összegző következtetés
A hat vizualizáció együttesen azt mutatja, hogy a WTI határidős árak a vizsgált ~egy hónapban tartósan csökkentek, miközben a napi volatilitás és a kereskedési volumen jelentős ingadozást mutatott. A piac rövid távon kockázatos, hírérzékeny környezetet biztosított; hosszabb távú következtetésekhez természetesen több adat és fundamentális elemzés lenne szükséges.


