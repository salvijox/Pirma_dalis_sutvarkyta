# Pirma_dalis_sutvarkyta

# v0.5 versija

## Programos veikimo greičio analizė, kai naudojama sąrašai

*Skliaustuose nurodomas programos laikas v0.4 versijos*

**FAILAS SU 1000 įrašų:**
*	Failo su 1000 irasu nuskaitymo laikas: 0   *32ms (0     *41ms)
* Failo su 1000 irasu dalijimo i dvi grupes laikas: 0   *7ms (0    *20ms)

**FAILAS SU 10000 įrašų:**
*	Failo su 10000 irasu nuskaitymo laikas: 0    *311ms (1   *452ms)
*	Failo su 10000 irasu dalijimo i dvi grupes laikas: 0    *75ms (0   *228ms)

**FAILAS SU 100000 įrašų:**
*	Failo su 100000 irasu nuskaitymo laikas: 4    *4134ms (7    *4783ms)
*	Failo su 100000 irasu dalijimo i dvi grupes laikas: 1    *971ms (4    *2171ms)

**FAILAS SU 1000000 įrašų:**
*	Failo su 1000000 irasu nuskaitymo laikas: 43   *35046ms (65    *48152ms)
*	Failo su 1000000 irasu dalijimo i dvi grupes laikas: 12    *8545ms (33    *20263ms)

**FAILAS SU 10000000 įrašų:**
*	Failo su 10000000 irasu nuskaitymo laiko neapskaičiavo, dėl atminties užimtumo(trūkumo).

**Išvada: programa veikia greičiau naudojant list, kadangi iš senesnės programos laikų buvo sunku palyginti, tai programas sulyginau pakeitus laikų vienetus**

*Testavimo sistemos parametrai: CPU – 2 GHz, RAM – 8,00 GB, SSD – 128 GB, HDD – 1 TB *
