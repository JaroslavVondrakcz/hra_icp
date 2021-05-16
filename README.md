# Hra

Cíl hry: Přežít!! Ve hře se pohybuje příšera, která když vystopuje hráče, tak ho sežere (hra se restartuje a vygeneruje se nová mapa). Hráč má možnost postavit dva druhy kostek.  Jednu cihlovou a druhou ze skla. Cihlovou kostku příšera může přesunout a pokračovat v cestě. Hráč může ale do cesty příšeře postavit kostku ze skla. Jelikož se příšera bojí pořezání o sklo, tak se kostky nedotkne a nemůže jí přesunout. Hráče taková kostka stojí dvě cihlové kostky.
Na začátku hry má hráč 5 kostek (víc jich neunese).  Pokud hráč už nemá další kostky, může nějaké zníčit a postavit je jinam. 

#### Ovládání
- W, A, S, D - pohyb
- E - přepínání zbraně ničení/stavění
- F - změna kostky ciglová/skleněná
- L - zapnout/vypnout baterku
- I - zobrazení na celou obrazovku

#### Scéna 
- 3D scéna 
- načtení 3D objektu jako strop
- klávesnice (pohyb, změna zbraně, změna kostky, beterka...)
- myš (pohyb, zničení/vytvoření kostky)
- vlákno na pohyb příšery
- Průhlednost (skleněná kostka)
- textury (sklo, cigla, nezničitelné zdi)
- kolize (ničení kostek, příšera sežere hráče, nelze projít kostkou, nelze zničit zdi...)
- stop (simulace jeskyně)
