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
