---
layout    : wp
active    : 5
heading   : Webové publikovanie
date      : 2017-3-12
menu_file : wp_menu.html
---

{::options parse_block_html="true" /}
<div id="z1" class="tab-pane fade in active">
# Zadanie 1

### Cieľ
Cieľom prvého zadania bolo vytvoriť webovú prezentáciu (webové sídlo) so zameraním na moje záujmy a prezentáciu.
Bolo potrebná využiť technológiee Git, GitHub Pages, Jekyll a Markdown.

&nbsp;

### Požiadavky 
1. Sídlo musí obsahovať aspoň 5 podstránok, pri využití aspoň 3 rôznych rozložení (layout-ov)
2. V rámci šablon musí byť použité:
   - aspoň 5 premenných
   - kolekcie alebo dátové súbory
   - aspoň 5 filtrov alebo tagov
   - aspoň 1 plugin (okrem pagination)
   
&nbsp;

### Naplnenie požiadaviek
1. Stránka obsahuje **5 podstránok** na primeranej úrovni kvality. 
Každá z nich zapadá do celkového štýlu stránky. 
Tiež sa snažia dodržat aspon základné zásady responzívneho dizajnu.
Na vytvorenie graficky priatelného vzhladu som použil Bootstrap.
Odkazy na jednotlivé podstránky sa nachádzajú v hornom menu.
    - **Hlavná stránka**
    - **Životopis**
    - **Záľuby**
    - **Projekty**
    - **Webové publikovanie**
     
    &nbsp;

2. Stránka obsahuje **4 rôzne layouty** + jeden spoločný pre všetkých. 
Spoločný layout zabezpečuje hlavne zamedzenie opakovania rovnakých kúskov kódu ako je <!DOCTYPE html>, footer alebo horné menu.
Snahou bolo, aby bol každý jeden layout znovupoužiteľný bez nutnosti prepísať nejakú jeho časť čo sa aj podarilo najmä vďaka premenným a dátovým súborom
    - **default** - spoločný layout pre všetky ostatné layout-y. Obsahuje spoločné prvky.
    - **index** - layout špeciálne pre hlavnú stránku, ktorý obsahuje na vrchu jednoduchú minimalistickú prezentáciu osoby. 
                Dáta o tejto prezentácii (ako napríklad názov fotky alebo charakteristické slová) sa získajú z markdown súboru 
    - **normal** - je základný layout, ktorý neobsahuje nejaké špeciálne prvky. Je však veľmi vhodný a pekný na jednoduché články
    - **projects** - layout, ktorý obsahuje ľavé bočné menu, do ktorého je možné načítať súbor s menu pomocou premennej page.menu_file, ktorá musí byť definovaná v markdown súbore.
    - **wp**  - layout, ktorý obsahuje horné prepínacie menu. Menu sa načítava zo súboru podobne ako pri layout-e projects
 
    &nbsp;
 
3. Stránka obsahuje **5 vlastných premenných**
    - **active** - obsahuje jedinečné číslo, ktoré je tiež pridelené tlačidlu v hornom menu. 
            Táto premenná služi na detekovanie, ktoré okno je aktuálne aktívne a na základe toho sa dané tlačidlo v hornom menu zvýrazní.
    - **date** - premenná predstavuje dátum editácie. 
            Nastavuje ju používateľ sám a zobrazuje sa dole pod príspevkami spolu s menom autora
    - **heading** - premenná obsahuje podnadpis, ktorý sa prilepí k menu autora a zobrazí sa v tagu title. 
            Ak je premenná prázdna, miesto podnadpisu sa zobrazí iba nadpis
    - **profile_picture** - v tejto premennej je názov súboru v priečinku /assets/img , ktorý sa má zobraziť ako fotka autora. 
            Toto riešenie je výhodne aj kvôli jednoduchosti editácie a nezávislosti layout-u index na "hardcode-nutých" častiach kódu
    - **descr_words** - Obsahuje nejaké slová alebo aj vetu, ktoré chce mať autor napísané v rámci prezentácie osoby v layoute index

    &nbsp;
    
4. Stránka obsahuje **dva dátové súbory**, ktoré sa používajú na generovanie menu. 
Prípadná zmena v tomto súbore (napríklad pridanie nového tlačidla s odkazom) sa automaticky prejavuje v zmene vykresľovaného menu menu.

    &nbsp;

5. Stránka obsahuje ako **filtre** tak aj väčšie množstvo **tagov**. Filtre su použité napríklad na vytvorenie obsahu tagu title alebo na formátovanie dátumu (premenná date)
Tagy su použité napríklad pri skladaní obsahu tagu title alebo pri vytváraní horného menu prípadne menu pre projekty.
 
    &nbsp;
 
6. Stránka obsahuje **2 pluginy**. [YouTube Embed Plugin](https://gist.github.com/joelverhagen/1805814) a [Jekyll-Maps](https://github.com/ayastreb/jekyll-maps) 
Prvým je plugin na youtube videa, ktorý nie je potrebné inštalovať.
Použitý je v časti záľuby (nefunguje na GitHub Pages)
Druhý plugin sú Google Mapy, ktoré sú použité v časti index (teda hlavná stránka) a zobrazujú miesto, kde sa nachádza FIIT (nefunguje na GitHub Pages).
Druhý plugin je potrebné nainštalovať pomocou - *gem install jekyll-maps*

&nbsp;

### Dodatočné informácie
- Pluginy na Github Pages nefungujú. 
    Súbory ako Gemfile alebo config som preto upravil tak, aby tieto chyby nerobili problémy na GitHub Pages.
    Odovzdané úbory tak sú clonom z githubu s malou zmenou, aby stránka získala plnú funkcionalitu, ktorú jej GitHub Pages nevedeli zabezpečiť.
- [GitHub Pages odkaz](https://odkopp.github.io/ "GitHub Pages - OdkoPP")

&nbsp;
     
### Záver
Výsledkom projektu je pekná modernevyzerajúca stránka, ktorá spĺňa požiadavky zadania. 
S webom robím už dlho ale s nástrojom jekyll som sa ešte nestretol.
Je to relatívne jednoduchý nástroj, ktorému je jednoduché porozumieť.
Mohol som tak využiť vedomosti, ktoré som počas rokov v tejto oblasti získal a aplikoať ich na preňa novú technológiu.
Tento nástroj sa mi celkom páči aj ked má podľa mňa muchy. Je však možné že ho v buducnosti použijem znova.
     
</div>























<div id="z2" class="tab-pane fade" style="min-height: 500px">
# 2. Zadanie 

#### Štandardné členenie textu na kapitola, podkapitola, podpodkapitola, príloha, generovaný obsah
- Celý text je členený na kapitoly ( *`<chapter>`* ) a podkapitoly ( *`<section>`* )
- Celý dokument má automaticky generovaný obsah ( *`toc`* )

&nbsp;

#### Zvýraznenie slov, zvýraznenie členenia textu odrážkami alebo číslovaním
- Zvýraznené časti textu je možné nájsť napríklad ku koncu dokumentu ( *`5.1.`* )
- Zvýraznenie je pomocou 
    - Bold, Italic ( *`<emphasis>`*, *`<emphasis>`* )
    - Číslovania ( *`<orderedlist>`*, *`<listitem>`* )

&nbsp;

#### Odkazy na iné časti vlastného dokumentu, prípadne odkazy na URL
- V dokumente sa nachádza odkaz na časť vlastného dokumentu napríklad na začiatku 4. kapitoly, z kade sa odkazujem na analýzu ( *`<xref>`* )
- V poznámkach pod čiarou sa nachádza množstvo fungujúcich URL odkazov ( *`<ulink>`* )
- V literatúre sa nachádzajú tiež funkčné URL odkazy ( *`<ulink>`* )
 
&nbsp;

#### Poznámka pod čiarou
- Poznámok pod čiarou je relatívne veľa, pričom sa väčšinou jedná o URL na zdroj obrázkov alebo na rôzne systémy, ktoré boli v dokumente opísané. Je to teda spracované rovnako ako to bolo v pôvodnom dokumente na Bakalársky projekt ( *`<footnote>`* )

&nbsp;

#### Zoznam použitej literatúry a zdrojov vrátane ich citácie v texte
- Na konci dokumentu sa nachádza zoznam použitej literatúru ( *`<bibliography>`*, *`<bibliomixed>`* )
- V texte sa nachádzajú odkazy na túto literatúru, pričom väčšina z nich sa nachádza v Úvode ( *`<xref>`* )

&nbsp;

#### Vloženie obrázku a tabuliek, odkazy na ne v texte; zoznam obrázkov a tabuliek v úvode alebo závere textu
- V dokumente sa nachádza zopár obrázkov vrátane popisu ( *`<figure>`*, *`<emphasis>`*, *`<imageobject>`* ) a na každý je odkaz v texte ( *`<xref>`* )
- Na konci sa nachádza jedna tabuľka ( *`<table>`* ), ktorá bola naformátovaná do relatívne rovnakej podoby ako bola v pôvodnom dokumente vrátane hlavičky ( *`<thead>`* ), ale aj tela ( *`<tbody>`* ), pričom je rovnaké aj orámovanie ( *`rowsep`* )
- Niektoré obrázky sú zmenšené aby boli krajšie zobrazené ( *`width=”60%”`* )
- Na začiatku sa nachádza zoznam tabuliek a obrázkov ( *`table`*, *`figure`* )

&nbsp;

#### Vytvorenie registra pojmov (indexu) s pojmami hierarchicky usporiadanými do dvoch úrovni
- Na konci pred použitou literatúrou sa nachádza register pojmov, ktorý obsahuje požadovaný počet pojmov usporiadaných do dvoch úrovní. Zameral som sa na pojmy, ktoré majú podľa mňa význam pre tento dokument ( *`<index>`*, *`<indexterm>`*, *`<primary>`*, *`<secondary>`* )

&nbsp;

#### Prispôsobenia v XSLT
- Rozloženie elementov na úvodnej strane vrátane pridania nových.
- Odstránenie horného riadku s menom kapitoly (aby sa to podobalo na pôvodný dokument)
- Rola pre
    - abstrakt - použitá pre poďakovanie aby bolo dole na strane a nadpis naľavo
    - obrázok - medzera na spodnej časti obrázka
- Abstrakt má medzery medzi odsekmi (aby sa to podobalo na pôvodný dokument)
- Zmenené číslovanie obrázkov a tabuliek
- Odstránenie slova kapitola z názvu kapitoly. Ostalo iba číslo (automaticky generované) a za ním sa nachádza požadovaný názov kapitoly
- Podčiarknutie názvu kapitoly
</div>



<div id="z3" class="tab-pane fade" style="min-height: 500px">
# Zadanie 3

Táto časť stránky bude dopalnená dodatočne
</div>
