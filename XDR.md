# XDR, EDR, MDR

 Une entreprise comptant en moyenne 1 000 employés peut percevoir un pic allant jusqu’à 22 000 événements par seconde entrer dans son système de gestion des informations et des événements de sécurité (SIEM). Cela représente quasiment 2 millions d’événements en une journée.
Face aux nombreux journaux et alertes, mais en l’absence d’indicateurs clairs, il est difficile de savoir quoi chercher.il peut être difficile de cartographier son parcours et son impact dans l’organisation
La réalisation d’une investigation peut être un effort long et manuel, à condition toutefois que les ressources nécessaires soient disponibles. XDR automatise les enquêtes sur les menaces en éliminant les étapes manuelles, et fournit des outils et des données riches pour effectuer une analyse qui serait impossible autrement

XDR alimente les données d'activité de plusieurs couches vers un data lake. Toutes les informations applicables sont mises à disposition pour une corrélation et une analyse efficaces dans la structure la plus pertinente

## EDR

l’EDR est un outil de sécurité complémentaire de l’antivirus next gen avec lequel il travaille afin de bloquer les menaces connues comme inconnues (zero-days). C’est un outil qui se place sur les terminaux et non au niveau réseau d’un système d’information.  L’outil fait de l’analyse comportementale, et monitore les actions d’un terminal

Un EDR est caractérisé par ses capacités de détection, d’investigation et enfin de remédiation

### detection

L’EDR est capable de surveiller l’exploitation de failles de sécurités en surveillant les appels noyaux et les différents services habituellement ciblés notamment chez Windows
L’analyse comportementale permet de stopper un attaquant dans son élan. Par exemple si un pdf contient un script powershell pour ouvrir un port alors cette action sera bloquer par l'EDR

### Investigation

l’EDR permet d’observer des suites d’actions dont le résultat est des plus douteux
 Ainsi, si une attaque est détectée sur 5 cinq terminaux, alors la console centralisée va faire redescendre l’information sur tous les autres.

### Remediation

l’EDR a des capacités similaires à celles d’un antivirus next gen et peut notamment bloquer, supprimer et mettre en quarantaine des fichiers

## MDR

