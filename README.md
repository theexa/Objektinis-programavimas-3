# Objektinis-programavimas-3
## Programos diegimo instrukcija
### SVARBU:
* Jei turite admin prieiga - siuskites StudentSorterSetup, ji atitinka visus reikalavimus
* Jei admin prieigos neturite - siuskites Setup, ji pateikia alternatyvų kelią programos įdiegimo lokacijai
Taip atsitiko dėl to, kad pagal reikalavimus programos saugojimo kelias turi būti `C:/Program files/VU/Vardenis-Pavardenis`. Naudojant kompiuteri ne per "admin" paskyra, prieigos pakeisti šiems failams nėra, dėl to neleis iki galo parsisiųsti programos. Setup programa turi alternatyvų kelią `C:/Users/(username)/AppData/Roaming/Microsoft/Windows/Start Menu/Programs/VU/Vardenis-Pavardenis` kuris leidžia programą pilnai parsisiųsti be `admin`prieigos.
### Reikalavimai 
* Turėti C++ 17 plaikantį kompiliatorių
* Turėti bent 30MB laisvos vietos kompiliacijai
* Turėti CMake versiją ≥ 3.10
### Naudojant StudentSorterSetup.exe/Setup.exe
1. Parsisiųskite failą `StudentSorterSetup.exe`.
2. Atidarykite atsisiųstą failą.
3. Pasirinkite norimą failo saugojimo direktoriją (automatiškai nustatyta `C:/Program files/VU/Vardenis-Pavardenis\StudentSorter`, ir spauskite next.
4. Paasirinkite ar norite greitosios nuorodos į programą savo darbalaukyje, ir sapuskite next.
5. Install.
6. Finish.
#### Programos šalinimas
1. Savo kompiuteryje nueikite į `Control Center`.
2. Pasirinkite `Programs`.
3. Susiraskite programą `Student Sorter version 3.0`, patogu naudojant paiešką.
4. Pasirenkame ir spaudžiame `uninstall`.
---
## Programos naudojimosi instrukcija
1. Paleidžiame programą;
2. Pasirenkame konteinerio tipą;
3. Pasirenkame skaidymo strategija;
4. Pasirenkame ar norime kurti atsitiktinius failus:
4.1.  Jei taip pasirenkame kiek studentų norime;<br>
4.2.  Sukuriamas failas;<br>
5. Pasirenkame kaip programa gaus duomenis:<br>
5.1  Nuskaitymas iš failo; <br>
   Įvedame failo pavadinimą, iš kurio bus nuskaitomi duomenys;<br>
5.2  Įvedimas ranka; <br>
   Įvedame kiek studentų norėsime, ir tada jų duomenis (vardą, pavardę, pažymius, egzamino pažymį); <br>
6. Programa atlieka testavimą;
7. Ekrane išvedama 5 testavimų rezultatai - Vargšiukų kiekis, Kietiakų kiekis, Naudota strategija, Strategijos trukmė (vienam testui).
8. Po visų penkių testavimų taip pat pateikiamas apibendrinimas: Vidutinis testo laikas, ir bendras skaidymo laikas.
9. Gauname rezultatų failus: RezA - vidurkiai <5; RezB - vidurkiai >=5;
---
