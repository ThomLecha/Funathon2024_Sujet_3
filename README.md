# Funathon 2024 - Sujet 3 :star:

Datavisualiser les émissions de CO2 sur une carte mondiale entre pays en dynamique mois par mois, éventuellement à l’aide du package _leaflet_

## Grandes parties

1. Importer les données mensuelle de consommation depuis Min-IO

2. Calculer les émissions de CO2 avec le facteur 3,16 et les mettres dans une format adapté dans un dataframe

3. Utiliser le package _leaflet_ pour afficher les émissions de CO2 par mois et par pays

   - Se faire un compte sur _Stadia Maps_ pour bénéficier des fonds de carte

   - Afficher la carte dans RStudio

4. Faire la partie UI/FrontEnd du serveur Shiny
   - Créer une interface avec un panneau latéral et un panneau principal
   - Mettre des inputs (listes de sélection, bouton radio, curseur, etc.) dans le panneau latéral 
   - Utiliser les _leafletOutput_ du package _leaflet_ pour afficher les données en carte dynamique dans le panneau principal

5. Faire la partie Serveur/BackEnd du serveur Shiny
   - Relier les inputs et les outputs

## Remarques

Faire l'extraction depuis TARMAAC et placer les données sur Min-IO ([Tutoriel Min-IO](https://inseefrlab.github.io/docs.sspcloud.fr/docs/fr/storage.html))

Voir test de _leaflet_ [ici](https://github.com/ThomLecha/TestDeDataVisualisation)
