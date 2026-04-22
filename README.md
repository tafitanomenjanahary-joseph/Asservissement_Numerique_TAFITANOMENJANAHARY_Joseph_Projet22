# Asservissement_Numerique_TAFITANOMENJANAHARY_Joseph_Projet22
Ce projet présente la simulation d’un système hydraulique simple sous LabVIEW dans le cadre de l’asservissement numérique. Le niveau d’un réservoir est contrôlé par une commande proportionnelle. Le modèle discrétisé montre une bonne stabilité et une convergence vers la consigne
# Simulation d’un système hydraulique sous LabVIEW
## Description
Ce projet consiste à simuler un système hydraulique simple dans le cadre du cours d’asservissement numérique. Le système étudié est un réservoir dont le niveau est contrôlé par une commande proportionnelle.
## Objectif
- Modéliser un système hydraulique
- Implémenter le modèle sous LabVIEW
- Contrôler le niveau du fluide
- Observer la stabilité du système
## Méthode
Le modèle est basé sur une équation discrète :
h(k+1) = h(k) + dt*(Qin - k*h)
Une commande proportionnelle est utilisée :
Qin = Kp*(href - h)
## Paramètres
- Kp = 2
- href = 5
- k = 0.5
- dt = 0.1
## Exécution
1. Ouvrir le fichier principal du projet (fichier .vi) dans LabVIEW.
2. Accéder au Front Panel pour visualiser l’interface utilisateur.
3. Vérifier ou saisir les paramètres suivants :
Gain proportionnel : Kp=2
Consigne : href=5
Coefficient de sortie : k=0.5
Pas de temps : dt=0.1
4. Cliquer sur le bouton Run (flèche blanche) pour lancer la simulation.
5. Observer l’évolution du niveau du fluide :
sur l’indicateur numérique
sur le graphique (Waveform Chart)
6. Arrêter la simulation en cliquant sur le bouton Stop.
7. Modifier les paramètres si nécessaire pour analyser le comportement du système.
## Auteur
TAFITANOMENJANAHARY Martin Joseph
