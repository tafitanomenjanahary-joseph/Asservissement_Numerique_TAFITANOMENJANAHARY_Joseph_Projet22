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
1. Ouvrir le fichier .vi avec LabVIEW
2. Lancer le programme
3. Observer le graphique
## Auteur
TAFITANOMENJANAHARY Joseph
