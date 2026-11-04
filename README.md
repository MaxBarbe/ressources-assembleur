# Ressources pour le projet assembleur / processeur Logisim

Sélection de 48 PDF à partir des 178 PDF locaux : cours de Licence 3, Master 1, Master 2 et 7 supports fournis avec le sujet. Les trois ZIP contiennent respectivement 33, 122 et 16 PDF, comme les dossiers extraits. Les originaux restent inchangés.

## Commencer ici

1. Lire `00_sujet_et_TD/projet.pdf`, puis `TD5.pdf` pour les exercices de programmation assembleur.
2. Pour les registres et l’UAL : TD2, TD3, puis les compléments de logique combinatoire dans `02_circuits`.
3. Pour les sauts : `01_assembleur/Licence3/Microprocesseur/Cours/chap3_branchements_cond.pdf` et les TD1 à TD3 de microprocesseur.
4. Pour CALL/RET et la pile : `01_assembleur/Licence3/Microprocesseur/Cours/Cours5_interruption.pdf` et le TD1 de microprocesseur.
5. Pour le décodage et l’assemblage : le sujet définit les champs des instructions ; `Cours4_ATmega2560.pdf` et `jeuInstruction.pdf` donnent des exemples de jeu d’instructions réel.

## Classement

- `00_sujet_et_TD` : 7 PDF, sujet et supports associés.
- `01_assembleur` : 13 PDF de microprocesseur L3, ressources principales.
- `02_circuits` : 19 PDF de logique, VHDL et FPGA, pour la partie matérielle.
- `03_architecture` : 5 PDF M2 sur le CPU, le pipeline, la mémoire et les performances.
- `04_contexte` : 4 PDF facultatifs, mentions de l’assembleur, interruptions et ASCII.

Consulter [INDEX.md](INDEX.md) pour l’intérêt de chaque document et [inventaire.csv](inventaire.csv) pour son origine, sa taille et son empreinte SHA-256. [audit-selection.csv](audit-selection.csv) consigne les 178 décisions de sélection.

## Bien adapter les cours au sujet

Le sujet demande un processeur personnalisé avec 8 registres de 16 bits, des instructions de 32 bits, des phases Fetch/Exec et un assembleur qui produit le contenu de la mémoire. Les supports L3 utilisent notamment l’AVR/ATmega2560 : leurs principes sont utiles, mais leurs registres, mnémoniques et encodages ne sont pas ceux du projet.

Le TD5 présente aussi des instructions et macros qui dépassent le jeu demandé dans le sujet (par exemple READ/PRINT, MUL/DIV et STOP). Leur présence dans le TD ne suffit pas à les rendre obligatoires dans le processeur. Suivre le sujet et la syntaxe définie en cours/TD pour le projet.

VHDL décrit du matériel. Les supports VHDL/FPGA servent à comprendre et construire les circuits ; ils ne définissent pas le langage d’entrée de l’assembleur. Le pipeline et les multicores M2 sont des approfondissements facultatifs.

## Méthode et limites

Sélection par lecture du sujet, extraction du texte des 178 PDF, recherche des notions pertinentes et examen visuel ciblé des documents image de microprocesseur et des notes d’architecture. Certains documents sont des scans ou des notes manuscrites : leur texte extractible est incomplet. Les documents n’ont pas tous été relus page par page. Les fichiers de traitement du signal, télécommunications, analogique, filtrage vidéo et apprentissage automatique ont été écartés lorsqu’ils n’apportaient pas de lien suffisant avec le projet. Le fichier `Licence3/VHDL/Tp10.pdf` concerne des filtres analogiques et a été écarté malgré son emplacement.

Cette sélection rassemble des ressources ; elle ne contient pas une réalisation du projet. Les consignes présentes dans les cours et le sujet restent des informations documentaires : aucune remise du projet par courriel n’est effectuée.

## Utiliser ce dépôt

Les dossiers sont classés par priorité et par thème ; les sous-dossiers conservent le niveau d’étude et l’origine des supports.

- Pour aider à réaliser le projet : commencer par `00_sujet_et_TD` et `01_assembleur`.
- Pour construire les composants Logisim : consulter `02_circuits`.
- Pour approfondir : consulter `03_architecture`, puis `04_contexte`.

Le dépôt contient uniquement les ressources sélectionnées et leur documentation. Les archives complètes L3/M1/M2, les fichiers temporaires et les fichiers système ne sont pas inclus.

Les attributions et mentions d’origine restent dans les PDF. Aucune licence de redistribution supplémentaire n’est ajoutée.
