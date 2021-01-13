# Pirma_dalis_sutvarkyta

# v1.0 versija

1 strategija: Bendro studentai konteinerio skaidymas į du naujus to paties tipo konteinerius: "vargšiukų" ir "kietiakų". Tokiu būdu tas pats studentas yra dvejuose konteineriuose: bendrame studentai ir viename iš suskaidytų (vargšiukai arba kietiakai).

2 strategija: Bendro studentų konteinerio skaidymas panaudojant tik vieną naują konteinerį: "kietiakai", o vargšiukai lieka bendrame studentų konteineryje, o kietakai perkeliami į naują.


## Failas su 1000 įrašų
* list: Failo su 1000 irasu nuskaitymo laikas: 0.0372943
* list: Failo su 1000 irasu rusiavimas su sort funkcija laikas: 0.187106
* list: Failo su 1000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 0.0070356
* list: Failo su 1000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 0.0115766
*  *

* vector: Failo su 1000 irasu nuskaitymo laikas: 0.0319062
* vector: Failo su 1000 irasu rusiavimas su sort funkcija laikas: 0.389205
* vector: Failo su 1000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 0.0422674
* vector: Failo su 1000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 0.0315728

----------------------

## Failas su 10000 įrašų
* list: Failo su 10000 irasu nuskaitymo laikas: 0.306186
* list: Failo su 10000 irasu rusiavimas su sort funkcija laikas: 3.45897
* list: Failo su 10000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 0.0953259
* list: Failo su 10000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 0.129921
*  *

* vector: Failo su 10000 irasu nuskaitymo laikas: 0.441025
* vector: Failo su 10000 irasu rusiavimas su sort funkcija laikas: 3.11273
* vector: Failo su 10000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 0.311911
* vector: Failo su 10000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 0.371854

----------------------

## Failas su 100000 įrašų
* list: Failo su 100000 irasu nuskaitymo laikas: 3.31222
* list: Failo su 100000 irasu rusiavimas su sort funkcija laikas: 35.5417
* list: Failo su 100000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 0.754205
* list: Failo su 100000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 1.26376
*  *

* vector: Failo su 100000 irasu nuskaitymo laikas: 2.96233
* vector: Failo su 100000 irasu rusiavimas su sort funkcija laikas: 24.9359
* vector: Failo su 100000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 2.48616
* vector: Failo su 100000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 2.08939

----------------------

## Failas su 1000000 įrašų
* list: Failo su 1000000 irasu nuskaitymo laikas: 31.0988
* list: Failo su 1000000 irasu rusiavimas su sort funkcija laikas: 428.759
* list: Failo su 1000000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 7.41152
* list: Failo su 1000000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 13.5668
*  *

* vector: Failo su 1000000 irasu nuskaitymo laikas: 31.4423
* vector: Failo su 1000000 irasu rusiavimas su sort funkcija laikas: 264.852
* vector: Failo su 1000000 irasu dalijimo i dvi grupes laikas pagal 1 strategija: 26.1804
* vector: Failo su 1000000 irasu dalijimo i dvi grupes laikas pagal 2 strategija: 20.7472

### Išvada: ###
Programa su vektoriumi, studentų sąrašo dalinimas greičiau atliekamas naudojant 2strategiją. O programą su listais
studentų sąrašas greičiausiai padalinamas naudojant 1strategiją.  

*Apie tyrimą:*
*  *Tyrimas atliktas su 1000, 10000, 100000, 1000000 studentų duomenų failais;*
*  *Testavimo sistemos parametrai: CPU – 2 GHz, RAM – 8,00 GB, SSD – 128 GB HDD – 1 TB*
