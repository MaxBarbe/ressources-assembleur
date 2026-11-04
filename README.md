# Ressources assembleur

13 PDF à lire en priorité, suivis de 7 annexes de cours et de TP. Les fichiers principaux sont numérotés dans l’ordre de lecture conseillé pour le projet.

| Ordre | Niveau / origine | Fichier | Ce qu’il apporte | Pages utiles du PDF |
|---|---|---|---|---|
| 01 | Projet fourni | [01_Projet.pdf](01_Projet.pdf) | Définit les instructions et leur encodage sur 32 bits ; lire en priorité les parties Decode IR et programme d’assemblage. | 1–4 |
| 02 | Projet fourni | [02_TD_Programmation_assembleur.pdf](02_TD_Programmation_assembleur.pdf) | Exercices de programmation : calculs, tableaux, tri, récursivité et traduction du C. | 1–2 |
| 03 | L3 | [03_Cours_Introduction_assembleur.pdf](03_Cours_Introduction_assembleur.pdf) | Comprendre les machines à pile et à accumulateur, les modes d’adressage et l’évaluation d’expressions en instructions. | 17–18, 23–49 |
| 04 | L3 | [04_Cours_Branchements_conditionnels.pdf](04_Cours_Branchements_conditionnels.pdf) | Registre d’état, conditions, boucles et traduction de structures de contrôle ; exemples avec LDI, BREQ, LOAD et STORE. | 3–12, 13–37 |
| 05 | L3 | [05_Cours_ATmega2560_Adressage_instructions.pdf](05_Cours_ATmega2560_Adressage_instructions.pdf) | Registres et pile, modes d’adressage, opérations, branchements, chargements et stockages : référence détaillée pour comprendre une instruction. | 39–43, 56–70, 72–82 |
| 06 | L3 | [06_Cours_Sous_programmes_Pile_CALL_RET.pdf](06_Cours_Sous_programmes_Pile_CALL_RET.pdf) | Comprendre les appels imbriqués, CALL/RET, l’adresse de retour et la pile LIFO ; directement utile à la partie fonctions du projet. | 4–26 |
| 07 | L3 | [07_Reference_Jeu_instructions_ATmega2560.pdf](07_Reference_Jeu_instructions_ATmega2560.pdf) | Tables des mnémoniques, opérandes, opérations et flags : arithmétique p. 1, sauts/appels p. 2, décalages p. 3, transferts p. 4 et pile p. 5. | 1–5 |
| 08 | L3 | [08_TD1_Pile_accumulateur.pdf](08_TD1_Pile_accumulateur.pdf) | Écrire les suites d’instructions évaluant une expression sur machine à pile ou à accumulateur ; bon premier exercice. | 1–2 |
| 09 | L3 | [09_TD2_Boucles_adressage_AVR.pdf](09_TD2_Boucles_adressage_AVR.pdf) | Exemples et notes sur CPI/BRLT/LDI, boucles, calculs et adressage direct ou indirect. | 1–6 |
| 10 | L3 | [10_TD3_Programmes_sous_programmes_AVR.pdf](10_TD3_Programmes_sous_programmes_AVR.pdf) | Analyse de boucles LDI/SUBI/BRNE et exercices de multiplication, sous-programmes et passage de paramètres par pile. | 1, 3–4 |
| 11 | L3 | [11_Revision_Expressions_sauts_adressage.pdf](11_Revision_Expressions_sauts_adressage.pdf) | Révisions manuscrites : PUSH/POP, expressions, comparaisons, boucles et modes d’adressage. | 1–6 |
| 12 | L3 | [12_Notes_Conditions_boucles_switch.pdf](12_Notes_Conditions_boucles_switch.pdf) | Traductions manuscrites de if/else, while, do/while et switch en comparaisons et branchements. | 1–2 |
| 13 | L3 | [13_Notes_Programmes_et_tables_instructions.pdf](13_Notes_Programmes_et_tables_instructions.pdf) | Exemples de programmes sur pile/accumulateur, adressage, registre d’état et tables avec opcodes et branchements. | 1–5, 7–8 |

## Annexes : cours et TP complémentaires

| Ordre | Niveau / origine | Fichier | Ce qu’il apporte | Pages utiles du PDF |
|---|---|---|---|---|
| A01 | L3 | [A01_L3_Cours_VHDL.pdf](Annexes/A01_L3_Cours_VHDL.pdf) | Additionneur, logique conditionnelle, processus, registres et machines d’états : aide pour concevoir les composants du processeur. | 13–18, 44–46, 49–56, 63–66 |
| A02 | Dossier M1 | [A02_M1_Support_Circuits_combinatoires.pdf](Annexes/A02_M1_Support_Circuits_combinatoires.pdf) | Additionneurs, soustracteurs, comparateurs, multiplexeurs et décodeurs : utile pour l’UAL et le décodage des instructions. | 1–25 |
| A03 | M2 | [A03_M2_Cours_Architecture_processeur.pdf](Annexes/A03_M2_Cours_Architecture_processeur.pdf) | Étapes Fetch, décodage, exécution et mémoire ; puis dépendances entre instructions et registres pour approfondir. | 15–27, 74–81 |
| A04 | M2 | [A04_M2_Revision_Architecture.pdf](Annexes/A04_M2_Revision_Architecture.pdf) | Fiche de révision : étapes d’une instruction, aléas et dépendances RAW/WAR/WAW ; lecture complémentaire après les cours assembleur. | 4–5 |
| A05 | L3 | [A05_L3_TP2_Organigramme_microprocesseur.pdf](Annexes/A05_L3_TP2_Organigramme_microprocesseur.pdf) | Notes de TP : organigramme manuscrit d’un programme sur registres, pour préparer la traduction d’un algorithme en instructions. | 1 |
| A06 | M1 | [A06_M1_TP1_FPGA_Compte_rendu_Maxime.pdf](Annexes/A06_M1_TP1_FPGA_Compte_rendu_Maxime.pdf) | Ton compte rendu avec Amira Bouraoui et Sara Chibane : additionneur 32 bits, schémas et comparaison de configurations de pipeline. | 3–6 |
| A07 | M1 | [A07_M1_TP1_FPGA_Enonce.pdf](Annexes/A07_M1_TP1_FPGA_Enonce.pdf) | Énoncé associé : concevoir et tester les opérateurs arithmétiques ; utile pour comprendre les mesures du compte rendu. | 1–2 |
