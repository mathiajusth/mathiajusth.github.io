Tento material je urceny tak ludom ktory boli na debatnych a chcu si pripomenut co sme robili
, ako aj tym ktori tam neboli a nechu byt do konca zivota mimo.

Na poslednych dvoch debatnych sme sa venovali tomu ako mozme argumenty formalne/strukturovane zapisat.

## Formalny argument

Vseobecna forma, v ktorej mozno argument zapisat, a teda aj definicia toho co budeme pod formalnym argumentom mysliet, je
mnozina predpokladov a zaver.

```
- predpoklad 1 
             
- predpoklad 2 
      .
      .
- predpoklad n 
____________
zaver
```

napriklad

```
- V novinach pisali, ze Marian Kocner je mafian

- Vsetko co pisu v novinach je pravda
____________
Marian Kocner je mafian.
```

Na argumente nas primarne zaujimaju dve veci
- vyplyva zaver z predpokladov ? (*validita*, angl. *validity*)
- su predpoklady pravdive ?

Ak na obidve tieto otazky odpovieme ano, tak nazyvame argument platny! (angl. *sound*)

O horeuvedenom argumente napriklad mozme povedat, ze je validny (Ak vsetko co pisu v novinach je pravda a pisu tam ze M.K. je mafian, tak potom nevyhnutne M.K. musi byt mafian), ale na to aby bol platny by sme museli ukazat za obidva predpoklady naozaj platia, co by
v pripade `Vsetko co pisu v novinach je pravda`  bola zrejme velmi tazka uloha.

*Ked sa teda pozerame na silu argumentu je potrebne hodnotit dve veci.
Na jednej strane treba zhodnotit, ako velmi je zrejme (intuitivne pravdive) ze zaver musi z predpokladom vyplyvat. Na strane druhej, ako zrejme je ze predpoklady su pravdive? Cim menej zrejme / viac kontroverzne to je
tim viac casu zrejme bude potrebneho na to si to v debate obhajit.
Argument chceme postavit tak, aby bola jeho validita vcelku ocividna. Viac sa budeme v debate pravdepodobne venovat dokazaniu pravdivosti predpokladov. To mozme spravit napriklad tak,
ze poskytneme dalsi argument,
ktory ma za ciel dany kontroverzny predpoklad dokazat .
Teda tento predpoklad bude zaverom v novom argumente.
Mozme si to predstavit naprilad takto*
```
argument 1: 
  - kontroverzny predpoklad
  - nejaky dalsi predpoklad
  ___________________
  teza ktoru chceme dokazat

argument 2: 
  - novy predpoklad 1
  - novy predpoklad 2
  - novy predpoklad 3
  ___________________
  kontroverzny predpoklad
```

*alebo vizualne viacvravne: *

```
teza ktoru chceme dokazat <--+-- kontroverzny predpoklad <--+-- novy predpoklad 1
                             |                              |
                             +-- nejaky dalsi predpoklad    +-- novy predpoklad 2
                                                            |
                                                            +-- novy predpoklad 3
```


### Ako obhajit Tezu?

Tak teraz vieme, co myslime pojmom formalny argument (predpoklady a zaver) a co znamena jeho validita a platnost.
Ako ale pouzit formalny argument na obhajenie nejakej tezy?

#### Dokazat tezu

Asi ocividna moznost je postavit tezu ako zaver a skusit vymysliet platny (sound) argument. Napriklad pre tezu
(ktoru sme mali na prvom debatnom)

```
Richard Sulik by mal odist z politiky.
```

sme prisli s niecim ako

```
- R.S. sa stretaval s Marianom Kocnerom
- M.K. sa nachadzal na mafianskych zoznamoch
- R.S. bud vedel, ze je M.K. na mafianskych zoznamoch, alebo mafianske zoznamy necital
- Ak politik necita mafianske zoznamy je nekompetentny
- Ak sa politik stretava s niekym o kom vie, ze je na mafianskych zoznamoch je nedoveryhodny
- Ak je politik nekompetentny alebo nedvoveryhodny, mal by odist z politiky
___________________
R.S. by mal odist z politiky
```

Prvotna nestrukturovana myslienka bola:

```
R.S. by mal odis z politiky, lebo sa stretaval s mafianom Marianom Kocnerom.
```

Tu sme formalne zapisali ako

```
- R.S sa stretaval s M.K.
- M.K. je mafian
__________________
R.S. by mal odis z politiky
```

Je tento argument validny?
Zial, nie je zrejme ako by mal zaver vyplyvat z predpokladov.
Musime pridat nejaky predpoklad.
Je tu nieco s cim iplicitne ratame ale neuviedli sme to explicitne ako predpoklad?

```
- R.S sa stretaval s M.K.
- M.K. je mafian
- Kazdy politik ktory sa stretava s mafianom
  by mal odist z politiky
__________________
R.S. by mal odis z politiky
```

Toto uz vyzera celkom validne. Su ale vsetky predpoklady pravdive?
Co keby sa R.S. brani: "Ja som nevedel, ze je mafian."
Na co tymto utoci?
Na platnost tvrdenia `Kazdy politik ktory sa stretava s mafianom by mal odist z politiky`
My chceme samzorejme tomuto utoku predist, tak argument pozmenime

```
- R.S sa stretaval s M.K.
- M.K. je mafian
- Kazdy politik ktory sa stretava s clovekom o ktorom vie ze je mafian
  by mal odist  politiky 
__________________
R.S. by mal odis z politiky
```

Teraz nam platia predpoklady, ale pokazili sme validitu :(
Potrebujeme ako predpoklad pridat `R.S. vedel, ze M.K. je mafian`.
My mu ale nevidime do hlavy a nemame k dispoizii ziadne vystupenie z doby ich stretnuti
z ktoreho by sa toto dalo odvodit.
Uvedomme si co sme zatial dokazali.

```
- R.S sa stretaval s M.K.
- Kazdy politik ktory sa stretava s clovekom o ktorom vie ze je mafian
  by mal odist  politiky 
___________________
Ak R.S. vedel, ze M.K. je mafian mal by R.S. by mal odis z politiky
```

Nedokazali sme teda tezu, iba za predpokladu, ze R.S. o tom vedel.
Zvolime teda **taktiku rozdelenia na pripady** - mame dve moznosti:
Bud R.S. vedel je M.K. je mafian, alebo to nevedel.
Uz sme dokazali prvy pripad - ze ak to vedel mal by odist.
Teraz teda musime dokazat druhy pripad - ze by mal odist aj ak to nevedel

```
- R.S. sa stretaval s Marianom Kocnerom
- M.K. bol mafian
- (rozdelenie na pripady)
  R.S. bud vedel, ze je M.K. mafian
  alebo nevedel ze M.K. je mafian             
- (dosledok pripadu 1)
  Ak politik nevie ci sa stretava s mafianmi
  tak je nekompetentny                        
- (dosledok pripadu 2)
  Ak sa politik stretava s niekym o kom vie ze je mafian
  tak je nedoveryhodny                        
- (spojenie pripadov)
  Ak je politik nekompetentny alebo nedvoveryhodny
  tak mal by odist z politiky 
___________________
R.S. by mal odist z politiky
```

Teraz je argument aj validny, aj dokazuje tezu ktoru sme chceli!
pozrime sa teda znova na jednotlive prerpoklady a ich silu.
Najslabsie teraz posobi `M.K. bol mafian` - nie je zrejme co myslime slovom mafian
a nijako sme to nedokazali. Skusime teda zvolit niec uchopitelnejsie - pouzijeme
fakt ze sa M.K. uz v tom case nachadzal na mafianskych zoznamoch a dostaneme
argumentaciu ktoru som uviedol na zaciatku.

*V tomto momente nie je zrejme, ako urcujume validitu argumentu. Pouzivame na to "len cit", ktory
nam hovori ci je predstavitelne ze zaver neplati ak platia vsetky predpoklady. Zrejme ste si vsimli
ze vety ktore pouzivame ako predpoklady (ci zaver) sa casto strukturalne podobaju. Viacere vety su typu*
- *ak ... tak ...*
- *... alebo ...*

*ci dokonca ja kombinacie.*

- *ak (... alebo ...) tak ...*

*Prave podrobnejsi pohlad na struktury viet a nasledna formalizacia ich zapisovania nam moze odhalit zakonitosti validity.
Zatial sme vsak formalizovali iba podobu arguemntu ako celku a ako premisy a zaver sme pouzivali hocijake vety z prirodzeneho jazyka.
Takze vysvetelnie tychto zakonitosti mozme presetrit niekedy nabuduce, ak vas to bude zaujimat. Ich pochopoenie znacne zjednodusi
a zautomatizuje tvorenie argumentov, ale urcite si to vuzaduje aspon par hodin zamyslenia sa a osvojenia si.*

#### Predpokladat tezu

TODO later
