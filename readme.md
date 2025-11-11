# > Gridek használata <
A gyerek elemeket vízszintesen rendezi a szülő elemben.
### align-content:
Több soros tartalom sorait rendezi felül, középre vagy alulra.
### align-items:
A gyerek elemeket egy sorban függőlegesen igazítja.
### display: grid;:
A szülő rácsos konténer lesz, amiben a gyerekek rácsban helyezkednek el.
### grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
Annyi oszlopot csinál, amennyi elfér és ezek minimum 200px szélesek.
### grid-auto-flow: columns/rows;
Megadja, hogy az új elemek sorban vagy oszlopban kerüljenek a rácsba.
### grid-template-rows: 100px 1fr auto;
Sorok magasságát adja meg, pl. fix, rugalmas vagy a tartalomhoz igazodó.
### direction: rtl/ltr;
A szöveg és a layout irányát állítja, balról jobbra vagy jobbról balra.
### grid-template-areas: "h h" "ar as";:
Neveket ad a rácsterületeknek, hogy könnyen el tudd helyezni az elemeket.
### grid-area: h;:
Itt a szülő oldalon rajzolja fel a rács neveit, itt határozza meg hol helyezkedjenek majd el.
### order:
Meghatározza, milyen sorrendben jelenjenek meg a gyerek elemek.