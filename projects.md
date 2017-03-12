---
layout    : projects

active    : 4
heading   : Projekty
date      : 2017-3-5
menu_file : projects_menu.html
---

&nbsp;

&nbsp;


# {{ page.heading }} {#p}

V tejto sekcii sa nachádzajú moje aktuálne, ale aj staršie projekty spolu s popismi k nim. Na týchto projektoch som pracoval hlavne z vlastnej iniciatívy.
Zo starších projektov tu dám predovšetkým také, ktoré sú dostupné online, prípadne v krátkom čase by mali pribudnúť na môj [github účet](https://github.com/OdkoPP "Github OdkoPP").
Môžete si ich teda pozrieť, prípadne vylepšiť.

&nbsp;

&nbsp;

# Aktuálne projekty {#p10}

### Bakalárska Práca {#p11}
Moja bakalárska práca je na tému *Pokročilé vyhľadávanie a vizualizácia*. 
Je to implementačne zameraná bakalárska práca, ktorej výsledkom má byť systém podobný [Semantic Scholar](https://www.semanticscholar.org/ "Semantic Scholar") alebo [ResearchGate](https://www.researchgate.net/home "ResearchGate").
Systém bude v podobe webovej aplikácie a bude pracovať s publikačnou činnosťou STU. 
Cieľom nie je urobiť celý systém od základov nanovo a tak nahradiť [pôvodný systém](publview.stuba.sk "PMS STU").
Ide skôr o zjednodušenie práce zamestnancom školy, pre ktorých je práca so starým systémom veľmi zdĺhavá a náročná.
Môj systém by mal urobiť veľa práce za zamestancov (podrobné vyhľadávanie, príťažlivá a jednoduchá vizualizácia dát a štatistík) a tak im spríjemniť prácu s týmito dátami.

Predpokladaný čas dokončenia projektu : Koniec apríla 2017

&nbsp;

&nbsp;

### Štatistiky NHL {#p12}
Začiatkom roka 2017 som začas stávkovať.
S kamarátom sa zameriavame predovšetkým na zápasy NHL.
Nemôžem povedať, že by som bol úspešný, ale som iba na začiatku.
Pred vykonaní stávok analyzujeme zápas, aby sme urobili konečné rozhodnutie, na ktorý tím pôjde naša dnešná stávka.
Pritom berieme do úvahy rôzne vstupy, ktoré by mohli zápas ovplyvniť.
Tieto prehľady robíme ručne ale radi by sme to spresnili, zjednodušili a zautomatizovali.

Preto som sa rozhodol vytvoriť sadu "parsrov" na rôzne webové stránky, ktoré by z nich vedeli získavať potrebné dáta.
K tomu bude existovať aj webová aplikácia, ktorá bude tieto dáta zbierať analyzovať a vyhodnocovať.
Využijú sa aj niektoré obmedzené REST API, ktoré mierne uľahčia prácu a vyhneme sa drahým REST API, ktoré tieto dáta ponúkajú už spracované.
Projekt je momentálne iba v začiatočnej fáze ale už je možné pomocou JS scriptu spracovať zápas a získať tak podrobné dáta v tvare JSON.
Ďalšie verzie by mali vedieť získať zranených hráčov, tzv. štatistiku Play-by-play, z ktorej bude možné získať veľmi podrobné dáta o priebehu hry. 
Neskôr možno bude možné k týmto dátam priradiť aj zostavy tímov, ktoré boli v čase rôznych udalostí (ako je vyhraté bulli, faul, gól a podobne) na ľade alebo pozície, na ktorých sa tieto udalosti v rámci ihriska udiali.
K týmto dátam sa pripoja aj dáta, ktoré sa nebudú meniť ako napríklad matica vzdialeností tímov, ich zaradenie do divízií alebo nejaký index rivality (na Slovensku by sme to nazvali derby).

Takéto informácie by mohli pomôcť pochopiť, ktoré veličiny sú v priebehu zápasu kľúčové, ktoré na sebe závisia a ktoré nie.
Bolo by tak pravdepodobne možné aspoň trochu presnejšie povedať, s akou pravdepodobnosťou vyhrá konkrétny tím.

&nbsp;

&nbsp;

# Staršie projekty {#p20}

### Facebook Time Counter {#p21}
[Facebook Time Counter](https://github.com/OdkoPP/Facebook_Time_Counter_GM "Github projekt - Facebook Time Counter") je [Greasemonkey](https://addons.mozilla.org/sk/firefox/addon/greasemonkey/ "Greasemonkey plugin") script, ktorého cieľom je upozorniť používateľov Facebooku na to, koľko času AKTÍVNE trávia za touto stránkou.
Script nahradí odkaz na hľadanie nových priateľov počítadlom, ktoré sa spustí vždy, keď je okno s Facebook-om aktívne, teda tam používateľ vykonáva nejakú činnosť.
Tento script eviduje aj sedem-dňovú históriu týchto časov. Používateľ si tak možno vstúpi do svedomia a rozhodne sa tento čas znížiť. 
Hlavný problém je to, že človek nevie, koľko času vlastne na Facebook-u bol lebo popri tom robil aj niečo iné. 
Keď sa ale takéto útržky spočítajú výsledne číslo vyráža dych.

Script má síce muchy, ktoré odstránim v ďalších verziách ale svoju funkciu dokáže z veľkej časti naplniť.

&nbsp;

&nbsp;

### See Post Only Once {#p22}
*See Post Only Once* je momentálne ešte nepublikovaný ale už funkčný [Greasemonkey](https://addons.mozilla.org/sk/firefox/addon/greasemonkey/ "Greasemonkey plugin") script, ktorý sa snaží zamedziť zobrazovaniu sponzorovaných príspevkov a viacnásobnému pozeraniu rovnakého príspevku na Facebook-u.
Teda príspevok, ktorý som už videl nebude zobrazený nikdy viac. 
Zabráni sa tak nezmyselnému opakovanému "scrollovaniu".
Po tom ako cez príspevok prejdem myšou, zobrazí sa okolo neho červený rámček.
Zaradí sa tak jeho ID na blacklist a pri novom načítaní stránky sa príspevky z blacklistu nezobrazia.
Síce tam budú načítané ale nebudú viditeľné. 
News-feed tak zostane prázdny, prípadne bude obsahovať iba nové príspevky, ktoré vidím prvý krát.
Script odstraňuje aj iné prvky stránky, ktoré by mohli lákať na prokrastináciu.

&nbsp;

&nbsp;

### YoutList {#p23}
[YoutList](https://github.com/OdkoPP/YoutList "Github projekt - YoutList") je [Greasemonkey](https://addons.mozilla.org/sk/firefox/addon/greasemonkey/ "Greasemonkey plugin") script, ktorý dovoľuje v rámci stránky Toutube vytvárať dočasné playlisty v zmysle čo bude hrať ďalšie.
Používateľovi sa pri videách na boku, z ktorých väčšinou vyberá nasledujúce video zobrazí dodatočné tlačidlo, ktorým je možné pesničku zaradiť do playlistu.
Celé prehrávanie sa následne riadi práve týmto vytvoreným playlistom.
Viem si tak vytvoriť taký playlist, aký práve chcem a nestojí ma to takmer žiadne úsilie. 
Tiež si viem takto jednoducho definovať napríklad pesničky, ktoré budú hrať ako ďalšie.
Nemusím sa teda stále preklikávať na youtube a vyberať stále jednu pesničku, ktorú chcem počuť ale definujem si piesne napríklad na 20 minút dopredu.
Video sa po skončení automaticky a okamžite presunie na ďalšie video v poradí a začne sa prehrávať. 
Videné video sa z playlistu odstráni.
Je tiež možné odstrániť video z playlistu.

Projekt je funkčný ale zišlo by sa mu krajšie používateľské rozhranie (momentálne sa zoznam nasledujúcich pesničiek zobrazuje na boku a nijakým spôsobom sa neskrýva).
Tiež by bolo vhodné obohatiť funkcionalitu, napríklad o preusporiadanie videí v playliste.