# Modélisation numérique du trafic routier : Domaines paramétriques d'émergence des embouteillages

<a href="https://thibautlavenant.github.io/phyMod_miniproject/Mod%C3%A9lisation%20num%C3%A9rique%20du%20trafic%20routier%20-%20Domaines%20param%C3%A9triques%20d'%C3%A9mergence%20des%20embouteillages.html">Contenu du rapport</a>

## Auteurs

Lavenant Thibaut
Benjamin Seo

## Description

Sur la route, le souhait commun est d'effectuer son trajet le plus rapidement possible. La plupart du temps en respectant le code de la route et sans collisions. Pourtant, il n'est pas rare d'observer un phénomène d'embouteillage alors même qu'il semble n'y avoir aucun obstacle ou raison de ralentir. Cela va à l'encontre de ce souhait global de se déplacer rapidement. Pour comprendre l'émergence de ce phénomène, nous proposons de modéliser une portion de route du point de vue de chaque automobiliste.

Notre hypothèse initiale considère que ce phénomène sub-optimal global provient d'une recherche d'optimisation individuelle. C'est un effet bien connu en théorie des jeux, et nous cherchons à savoir quels paramètres du comportement des usagers mènent à ce phénomène d'embouteillage. Une hypothèse annexe propose que pour un même comportement des usagers, les paramètres de circulation (comme la vitesse maximale et la densité) peuvent faire émerger ou non des embouteillages.

La circulation routière est un phénomène physique assez complet et déterministe étant donné l'input du conducteur. Notre modélisation est constituée de 2 parties :
- La modélisation de l'action du conducteur
- La modélisation de la cinématique de la voiture

La modélisation du conducteur se base sur l'environnement de la voiture. Le conducteur capte certaines informations et réagit en fonction. Soit par une accélération positive (accélérateur), soit par une accélération négative (frein), soit par une accélération nulle. Ces accélérations sont conditionnées par les capacités de la voiture et par la réaction minimum de l'automobiliste.

Nous présentons dans un premier temps plusieurs modélisations numériques d'un conducteur. Cela permet de comparer les profils de vitesse des différents modèles et nous a permis de choisir le plus adapté à l'analyse finale de l'impact des paramètres. Pour valider l'espace de paramètres de notre simulation, nous conduisons une expérience avec mesure d'accélération. Enfin, avec le bon algorithme de modélisation et l'espace de paramètres possible, nous cherchons à séparer l'espace en 2 zones distinctes. Une zone où une petite perturbation n'induit pas d'embouteillage (la perturbation est amortie) et une zone où la perturbation s'amplifie et se propage parmi les voitures. Le résultat de cette séparation nous permettra ainsi de répondre à la question initiale sur l'impact des paramètres comportementaux du conducteur.

## Génèse

Dans le cadre de l'UE Modélisation numérique de la License 2 PAD de la Sorbonne (https://phys-mod.github.io/source/intro.html#) nous avons produit un travail de modélisation numérique du trafic routier. 

## Citations

Mouhali, W. (2021, 8 juillet). Comment se forment les embouteillages ? The Conversation. https://theconversation.com/comment-se-forment-les-embouteillages-163994

Alokin-Fr. (2022, 1 juillet). GitHub - alokin-fr/road-traffic-simulation : Un simulateur de trafic routier se basant sur le modèle microscopique « Intelligent Driver Model » afin notamment d’étudier la formation d’embouteillages. GitHub. https://github.com/alokin-fr/road-traffic-simulation

Wikipedia contributors. (2022, September 5). Intelligent driver model. In Wikipedia, The Free Encyclopedia. Retrieved 10:09, April 30, 2024, from https://en.wikipedia.org/w/index.php?title=Intelligent_driver_model&oldid=1108624771

Zahorec, Pavol; Papčo, Juraj; Pašteka, Roman; Bielik, Miroslav; Bonvalot, Sylvain; Braitenberg, Carla; Ebbing, Jörg; Gabriel, Gerald; Gosar, Andrej; Grand, Adam; Götze, Hans-Jürgen; Hetényi, György; Holzrichter, Nils; Kissling, Edi; Marti, Urs; Meurers, Bruno; Mrlina, Jan; Pastorutti, Alberto; Scarponi, Matteo; Sebera, Josef; Seoane, Lucia; Skiba, Peter; Szűcs, Eszter; Varga, Matej (2020): The Pan-Alpine gravity database 2020. GFZ Data Services. https://doi.org/10.5880/fidgeo.2020.045

Illner, R., Bohun, C., McCollum, S., & van Roode, T. (2004). Mathematical modelling. https://doi.org/10.1090/stml/027

Lighthill Michael James and Whitham Gerald Beresford 1955On kinematic waves II. A theory of traffic flow on long crowded roadsProc. R. Soc. Lond. A229317–345
http://doi.org/10.1098/rspa.1955.0089

KHELIFI, A., LEBACQUE , J.-P. ., & HAJ-SALEM, H. . (2023). Modélisation stochastique macroscopique d’ordre supérieur du trafic sur les réseaux routiers : implications managériales. Revue Française De Gestion Industrielle, 37(2), 71–86. https://doi.org/10.53102/2023.37.02.1156

Le Monde De Jamy. (2017, 7 juillet). Le meilleur du Monde de Jamy - Comment se forment les bouchons ? [Vidéo]. YouTube. https://www.youtube.com/watch?v=wHz6S2dbYb4

## Crédit

Modélisation Numérique en Physique By P. Delva © Copyright 2022 CC BY-NC-SA 4.0 DEED