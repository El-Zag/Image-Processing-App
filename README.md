### **Application de traitement d'image en JavaFX**

**Auteurs :** Eloïse Zaghrini, Amandine Bouguessa, Armelle Coutaux

Cette application permet de traiter une image de format .png ou .jpg avec différentes options.
Chaque opération peut être réalisée successivement

Importez une image avec fond (Seam Carving ne fonctionne pas sur les images sans fonds) et commencez !

Une fois vos opérations réalisées, enregistrez votre image (elle sera au format .png).

Voici les différentes opérations disponibles :

- **Recagrage de l'image (rognage)**

Dans cette fonctionnalité, l'utilisateur peut rogner l'image à gauche, à droite, en haut ou en bas, à l'aide de sliders.
Les valeurs données aux sliders gauche/haut sont le nombres de pixels qui seront rognés à gauche/en haut de l'image.
La taille de l'image (largeur/hauteur) moins les valeurs données aux sliders droit/bas sont le nombre de pixels à rogner à droite/en bas.

Choisissez la taille souhaitée puis appuyez sur "Traitement de l'image".

- **Mise à l'échelle**

Dans cette fonctionnalité, l'image est applatie à la taille souhaitée en conservant son intégralité.

Choisissez la largeur et la hauteur souhaitée et appuyez sur "Traitement de l'image".

- **Seam Carving**

Dans cette fonctionnalité, l'utilisateur peut redimensionner son image en utilisant la fonctionnalité du Seam Carving, en diminuant ses dimensions ou en les augmentant. Le SeamCarving repose sur le calcul des énergies des pixels de l'image ( en norme 1 ou 2 au choix de l'utilisateur ), et ensuite sur la suppression/le dédoublement des coutures de pixels ayant l'énergie la plus basse. Ce traitement permet de redimensionner l'image en gardant un maximum d'informations !

Choisissez la largeur et la hauteur souhaitée et appuyez sur "Traitement de l'image".

- **Interface de dessin**

Permet de dessiner sur l'image.
Choisissez la couleur souhaitée à l'aide des trois sliders Bleu/Rouge/Vert (visualisation dynamique dans le rectangle de couleur) et choisissez l'épaisseur de pinceau souhaitée.

Dessinez ce que vous voulez !

- **Undo/Redo**

Vous vous êtes trompé ? Pas de problème ! Revenez à vos actions précédentes, vous pouvez aussi revenir à l'action suivante.



