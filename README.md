# czech_ambipositions


## Czech

Tento repozitář obsahuje utříděné a označené materiály a konkordance, k nimž je odkazováno v bakalářské práci *„Tradici navzdory“ – možnost výskytu některých českých předložek na pozici následující komplementu.* Značení řádků se řídí následujícím klíčem:

**1** = běžné prepoziční užití v KWIC  
**2** = postpoziční užití v KWIC (soubory ve složce „clear“ obsahuje pouze takové výskyty)  
**3** = jiné užití (intranzitivní, překlep apod.)

V budoucím výzkumu může být členění provedeno jemněji.

Označení souborů jako „sample“ či „full“ naznačuje, zda se jedná o vzorek konkordance vyhovující dotazu v CQL či o celou konkordanci (to záviselo na arbitrárně stanovené hranici maxima 400 manuálně procházených výskytů, vzorky mají plošně velikost 300 řádků).

Složka „collocations“ obsahuje tabulky s kolokačními mírami vygenerované pro potenciální kolokáty rozhraním KonText vyvíjeným na ÚČNK (https://www.korpus.cz/kontext). První pozice značí frekvenci, druhá MI-score, třetí T-score a čtvrtá hodnotu logDice.

Složka „txtype“ obsahuje informace o frekvenci jednotlivých typů textů v konkordancích, kde je slovo „navzdory“ užito prepozičně/postpozičně.

Všechny citované texty pocházejí z korpusu SYN2020 (viz https://wiki.korpus.cz/doku.php/cnk:syn2020).  
KŘEN, M., V. CVRČEK, J. HENYŠ, M. HNÁTKOVÁ, T. JELÍNEK, J. KOCEK, D. KOVÁŘÍKOVÁ, J. KŘIVAN, J. MILIČKA, V. PETKEVIČ, P. PROCHÁZKA, H. SKOUMALOVÁ, J. ŠINDLEROVÁ, M. ŠKRABAL, 2020. SYN2020: reprezentativní korpus psané češtiny [online]. [cit. 2021-04-21]. Praha: Ústav Českého národního korpusu FF UK. Dostupný z: http://www.korpus.cz.

## English

This repository contains the data referred to in the bachelor thesis *The ability of some Czech prepositions to follow their complement*, sorted and annotated (on a basic level). The concordance lines are annotated as follows:

**1** = "normal", i.e. prepositional use of the adposition in KWIC  
**2** = postpositional use of the adposition in KWIC (only such lines are included in the files in the "clear" folder)  
**3** = different use (not an adposition, intransitive, errata etc.)

The annotation might be further refined for the purposes of the following research.

The files named like conc_adposition-full.csv contain the full concordances obtained through the respective CQL query. Concordances with over 400 lines were not analyzed in their entirety. Rather, a 300-line sample was taken. Such files are named conc_adposition-sample.csv.

The "collocations" folder contains files with the information about the analyzed ambipositions' potential collocates, found by the KonText interface/toolset developed by ÚČNK (https://www.korpus.cz/kontext). The first number on each line refers to the absolute frequency of the word in the analyzed sample, followed by MI-score (2nd position), T-score (3rd) and logDice (4th).

The "txtype" folder contains information about the distribution of text types in two concordances – one for the prepositional use of "navzdory", one for the postpositional.

All the cited items were sourced from the SYN2020 corpus (see https://wiki.korpus.cz/doku.php/en:cnk:syn2020).  
Křen, M. – Cvrček, V. – Henyš, J. – Hnátková, M. – Jelínek, T. – Kocek, J. – Kováříková, D. – Křivan, J. – Milička, J. – Petkevič, V. – Procházka, P. – Skoumalová, H. – Šindlerová, J. – Škrabal, M. "SYN2020: reprezentativní korpus psané češtiny." Institute of the Czech National Corpus CU FA, 2020. Available from http://www.korpus.cz.
