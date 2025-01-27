# Changelog des snapshots

## 202444a - 03.11.2024

Première snapshot de **Striving Fighter** !

## 202445a - 11.11.2024

### Nouveautés

- Ajout des textures des quatre premiers blocs du jeu : Terre, Herbe, Sable, Pierre.
- Ajout de la fenêtre des paramètres.
- Ajout du système de mise à niveau de carrière.
- Ajout du système de sauvegarde de la partie et des préférences utilisateur.
- Le jeu peut désormais être fermé en appuyant sur Échap.

### Améliorations

- Refonte de nombreux éléments de l'UI.

## 202446a - 17.11.2024

### Nouveautés

- Ajout du nom de la région actuelle en haut de l'écran.
- Ajout des fenêtres Souterrains et Carte du monde.
- Ajout des textures des boutons de l'inventaire, de l'atelier, des paramètres, des souterrains et de la carte du monde.
- Ajout du premier arrière-plan en jeu.
- Ajout d'un arrière-plan aux fenêtres de l'UI.
- Ajout d'un bouton permettant de quitter le jeu dans les paramètres.

### Améliorations

- Le bouton de mise à niveau de carrière est grisé lorsque aucune mise à niveau n'est possible.
- Les paramètres s'ouvrent désormais en appuyant sur Échap.
- Mise à jour du fichier de localisation.

### Corrections

- Les claviers AZERTY sont maintenant supportés.
- Correction d'un problème à cause duquel le compteur de dollars s'affichait trop à gauche sur des écrans ayant une résolution autre que 16/9.
- Correction d'un problème à cause duquel les boutons étaient cliquables avec la touche Espace.

## 202447a - 24.11.2024

### Nouveautés

- Ajout d'animations au bloc central.
- Ajout d'animations d'affichage et de masquage aux fenêtres de l'UI.

### Améliorations

- Modification de l'arrière-plan des fenêtres de l'UI.
- Refonte des boutons de sauvegarde dans les paramètres.
- Refonte du système d'affichage et de masquage des fenêtres de l'UI.
- Mise à jour du fichier de localisation.

## 202448a - 01.12.2024

### Nouveautés

- Ajout des textures des boutons de l'entrepôt et de la carrière.
- Ajout du système d'inventaire.

### Améliorations

- Modification du système d'affichage et de masquage des fenêtres de l'UI.
- Modification de certains éléments de l'UI de l'inventaire.

## 202449a - 08.12.2024

### Améliorations

- Refonte du système de blocs et d'inventaire.
- Refonte de certains sprites et textures.
- Le nombre d'emplacements dans l'inventaire par défaut est de 10.
- Modification des 10 arrière-plans des 10 régions du jeu.
- Mise à jour du fichier de localisation.
- De nombreux éléments importants ont été modifiés dans le code du jeu.
- Suppression du logo d'Unity au démarrage du jeu.

### Corrections

- Correction d'un problème à cause duquel un clic sur un bloc cassé faisait apparaitre momentanément un nouveau bloc avant d'en recharger un deuxième.

## 202450a - 15.12.2024

### Nouveautés

- Ajout de la carte du monde.
- Il est maintenant possible de changer de région en cliquant sur l'un des points de la carte du monde.

### Améliorations

- La touche Échap permet désormais de fermer les autres fenêtres de l'UI avant d'afficher les paramètres.

### Corrections

- Correction d'un problème à cause duquel certaines fenêtres de l'UI ne pouvaient pas être fermées correctement.

## 202451a - 24.12.2024

### Nouveautés

- Ajout des items de la Clairière Enchantée, qui ont chacun un taux d'apparition différent pour chaque souterrain.
- Ajout des adversaires de la Clairière Enchantée, qui ont 10 % de chance d'apparaitre à la place du bloc central, et un taux d'apparition différent pour chaque souterrain.
- Ajout de 20 emplacements dans l'entrepôt.
- Ajout de l'icône du jeu.

### Améliorations

- Suppression des fenêtres de l'entrepôt et de la carrière.
- Les paramètres sont désormais indiqués comme étant "en cours de développement" : il s'agit d'une fenêtre temporaire qui sera retravaillée bientôt.
- Les points de la carte sont maintenant verrouillés lorsqu'une région n'a pas encore été débloquée par le joueur.
- Suppression du fondu au noir de l'arrière-plan du jeu lorsque le joueur tente d'accéder à la région dans laquelle il se situe déjà.
- Suppression du fondu au noir au démarrage du jeu.
- Au démarrage du jeu, l'adversaire ou le bloc chargé en premier n'est plus le dernier qui était apparu avant la sauvegarde de la partie, mais un tout nouvel adversaire ou bloc.
- Déplacement du compteur d'items dans un emplacement de l'inventaire ou de l'entrepôt et ajout d'une ombre derrière celui-ci.
- Modification de l'écran de chargement du jeu.
- Ajout d'une ombre derrière le bloc ou l'adversaire central.
- Suppression du voile noir au passage de la souris sur le bloc ou l'adversaire central.
- De nombreux éléments importants ont été modifiés dans le code du jeu.
- Mise à jour du fichier de localisation.

## 202452a - 29.12.2024

### Corrections

- Correction d'un problème à cause duquel l'icône du jeu ne s'affichait pas correctement sur Android.

## 202501a - 06.01.2025

### Nouveautés

- Ajout des barres de vie et d'énergie du joueur.

### Améliorations

- La version d'Android minimale pour lancer le jeu est désormais Android 6.0 (API level 23).

### Corrections

- Correction d'un problème à cause duquel le nom de certains adversaires ne s'affichait pas complètement au-dessus de l'entité centrale.

## 202502a - 12.01.2025

### Nouveautés

- Ajout du nom du souterrain actuel sous le nom de la région.
- Ajout d'un slider permettant de changer la taille des éléments de l'UI.
- Ajout d'un bouton permettant de réinitialiser les préférences du jeu dans les paramètres.
- Ajout d'une fenêtre d'information, qui comporte notamment les barres de vie et d'énergie du joueur, à gauche de l'entité centrale.

### Améliorations

- D'importantes modifications ont été apportées à l'UI afin que les éléments visuels s'adaptent à toutes les résolutions et définitions d'écran.
- Modification de l'animation de changement de région et de souterrain.
- Suppression d'un voile qui apparaissait lorsque l'entité centrale était cliquée.
- Le score n'augmente plus désormais lorsque l'entité cliquée est un adversaire.
- Un changement de région ou de souterrain ferme désormais toutes les fenêtres de l'UI.
- Déplacement de quelques épingles de la carte du monde.
- Mise à jour du fichier de localisation.

## 202503a - 20.01.2025

### Nouveautés

- Ajout d'un compteur de FPS en haut à gauche du compteur de dollars, qui peut être désactivé dans les paramètres.

### Améliorations

- Modification de la fenêtre des statistiques à gauche de l'entité centrale.
- Prise en charge des "zones sûres" des appareils mobiles : si les bords de l'appareil sont arrondis ou si une caméra frontale est présente par exemple, aucun élément important de l'UI sera caché.

### Corrections

- Correction de quelques problèmes de performances que les joueurs pouvaient rencontrer.
- Correction d'un problème à cause duquel le jeu se lançait avec une taille d'interface trop grande.

## 202504a - 27.01.2025

### Améliorations

- Optimisation du système d'ouverture et de fermeture des fenêtres de l'UI.
