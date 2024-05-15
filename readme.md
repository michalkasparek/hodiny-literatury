Hodiny literatury vypisují vedle přesného času i úryvek z české beletrie, který tento (nebo jemu velmi blízký) čas zmiňuje.

Hodiny literatury běží na [michalkasparek.cz/hodiny.html](https://michalkasparek.cz/hodiny.html). Zde si můžete stáhnout JSON s časy a ukázkami a využít jej třeba ve vlastnoručně vyrobených fyzických hodinách.

Inspirace: [Literature clock](https://literature-clock.jenevoldsen.com/).

To-do (klidně mi s tím můžete pomoct, tohle je GitHub, ne Národní galerie):

- Doplňovat další časy (viz prázdná místa níže). Nejsnazší způsob, jak přispět: [pošlete mi e-mail](mailto:michal.kasparek@gmail.com) s objevem.

- Navyšovat diverzitu ukázek: momentálně dominují detektivky, válečné romány a knihy psané muži. Dále se lidé v ukázkách často koukají na hodinky nebo na pendlovky a vidí na nich „x hodin a y minut“. Ona je to totiž fuška časy v knihách najít. Nejdřív jsem to strojově hledal v e-boocích postahovaných z [MKvP](https://www.mlp.cz/cz/katalog-on-line/eknihy/), pak jsem sáhl po [Digitální knihovně](https://www.digitalniknihovna.cz/), kde je víc textů, ale nejde je bagrovat regulárními výrazy. 

- Skrýt řádek s odkazy, pokud se se stránkou neinteraguje.

- Zobrazovat čas správně česky s tečkou mezi HH a MM a také se sekundami.

- Doplnit temný režim: buď ruční přepínání, nebo automatické v závislosti na nastavení systému.

Co dělá dobrou ukázku dobrou ukázkou:

- I přes titěrný rozsah funguje jako samostatná povídka, živý obraz.

- Je z ní hned poznat, jestli jde o čas dopolední, nebo odpolední.

- Popisuje přesný čas originálně.

*** 

 Přehled zanesených časů:

~~~
00 ▓▓▓░░▓░░░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░  
01 ▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░░▓░░░▓░▓░░░░░░░░░░░░▓░░░░░░░░░▓░░░░  
02 ▓░░░░▓░▓░▓▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░░░░░░░░░░░▓░░░░░░░░░░░░░░  
03 ▓░░░░░░░░░░░░░░▓░░░░░░░░░░░░░░▓░░░░▓░░░░░░░░░▓░░░░░░░░░░░▓▓░  
04 ▓░░░░░░░░░░░▓░░▓░░░░▓░░░░░░░░░▓░░░░▓░░░░░░░░░▓░░░░▓░░░░░░░░░  
05 ▓▓░░░▓░░░░░░░░░▓░░░░▓░░░░░░░░░▓░░░░░░▓░░░░░░░▓░░░░▓░░░░▓░░░░  
06 ▓░░░░░░░░░░░▓░░▓░░▓░▓░░░░░░░▓▓▓░░░░▓░░░░▓▓░░░▓░░░░▓░░░░▓░░░░  
07 ▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░▓▓░░░▓░▓░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░  
08 ▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░░░░▓░▓░░▓░░░░  
09 ▓░░░░▓░░░░▓░▓░▓▓░░░░▓▓░░░▓░░░▓▓░░▓░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░  
10 ▓░░░░▓░▓░░▓░▓░░▓░░░░▓░░▓▓▓░▓░░▓░░░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░▓░░  
11 ▓░░░░▓▓▓░░▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░  
12 ▓░▓░░▓░░░░▓▓░░░▓░▓░░▓░░▓░▓░▓░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░▓▓▓░░░  
13 ▓░░░░▓░░░░▓░▓▓░▓▓░░░▓░░░░▓░░░░▓░░░░▓░░▓░▓░░░░▓░░░░▓░░░░▓░░░░  
14 ▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░░░░▓░░░░▓░▓░░▓░░░░  
15 ▓░▓░░▓░░░▓▓░░░░▓▓░░░▓░░░░▓░▓░▓▓▓▓░▓▓░░░░▓░░░░▓░░░▓▓▓░░░▓░░▓▓  
16 ▓░▓░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░▓▓░▓░░▓░░░▓▓░░░░▓░░░░▓░░▓░▓░░░░  
17 ▓░░░░▓░░░░▓░░░░▓░▓░░▓░░░░▓░▓░▓▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░  
18 ▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░▓░▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░▓▓░  
19 ▓░░▓░▓░░░░▓░░░░▓░▓░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░▓░░▓▓░░░▓▓░░░▓░░░░  
20 ▓░░░░▓░░░░▓░░░░▓░░░░▓░░▓░▓░░░▓▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░▓░▓░▓  
21 ▓░░░▓░░░░░▓░░░░▓░░░░▓▓▓░░▓░░░░▓░░░░▓░░▓▓▓░░░░▓░░░░▓░▓░░▓░░▓▓  
22 ▓░░░░▓░░░░▓░░░░▓░░░░▓░▓░░░░░░░▓░░░░▓▓░░░▓░░░░▓░▓▓░▓░░░░▓░░░░  
23 ▓░░░░▓▓░▓░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░░░▓░░▓░▓░░░░▓░▓░░▓▓▓▓▓  
~~~