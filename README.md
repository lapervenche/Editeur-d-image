# Editeur d'image
Un site Web d'éditeur de photos léger
# Photo-Editor-Webapp

### Website link: https://github.com/lapervenche/Editeur-d-image

### Description:
Un site web d'édition de photos.

> This project was my final project for CS50 Course

### Projet Contenu:
- Fichiers html
- Fichier css
- Fichier javascript
- 1 dossier images

Le fichier javascript gère l'ensemble des manipulations d'images et contient toute la logique du site.

Le fichier CSS a quelques designs personnalisés et certains bootstrapant.

Enfin, les 20 vignettes d'image pour la conception du site.

### Comment utiliser cet éditeur d'image:

#### 1- Envoyer une image

Pour télécharger une image, cliquez sur la toile blanche au milieu de l'éditeur

Formats supportés:

- JPG
- PNG
- GIF
- WebP

#### 2- Contrôles

Au bas de la section de l'éditeur, il y a 3 boutons:

- Revenir à l'image d'origine ou en arrière
    Cliquez sur ce bouton pour retourner l'image éditée à son état d'origine

- Zoom In/Out
    Utilisez ces boutons pour zoomer/dézommer

- Télécharger
    Cliquez sur ce bouton pour ouvrir le menu de téléchargement

#### 3- Outils

3.1- Recadrer

Utilisez cet outil pour recadrer l'image

Exigences de l'outil:

- Rectangle
    - Spécifiez les coordonnées rectangulaires pour recadrer l'image
    - Gauche: la colonne de gauche 
    - En haut: la ligne supérieure 
    - Droite: la colonne de droite
    - En bas: la rangée inférieure

NOTE:

- Les valeurs gauche et droite ne peuvent pas être supérieures à la largeur d'image
- La valeur droite doit être supérieure à la valeur gauche
- Les valeurs supérieures et inférieures ne peuvent pas être supérieures à la hauteur de l'image
- La valeur inférieure doit être supérieure à la valeur supérieure

3.2- Rotation

Utilisez cet outil pour faire pivoter l'image

Exigences de l'outil:
- Angle
    - Specify an angle to rotate the image

Note:
- To rotate the image clockwise, use a negative value
- To rotate the image anticlockwise, use a positive value

3.3- Retournement

Utilisez cet outil pour retourner l'image

Exigences de l'outil:
- Axe
    - Spécifiez un axe pour retourner l'image sur elle même.

3.4- Texte

Utilisez cet outil pour ajouter du texte à l'image

Exigences de l'outil:
- Texte
    - Ecrivez dans cette boite le texte que vous souhaitez voir apparître sur votre image.
- Police d'écriture
    - Spécifiez une police d'écriture pour votre texte.
    - Utilisez le sélecteur de police pour choisir la votre.
- Taille de la police d'écriture
    - Spécifiez une taille en pixel (exemple: 18px) pour le texte à afficher.
    - Utilisez le sélecteur de taille pour spécifier celle ci.
- Couleur
    - Choisissez une couleur pour votre texte.
    - Choisir celle qui vous convient en utilisant le sélecteur de choix des couleurs.
- Position
    - Choisissez une position pour afficher votre texte dans l'image. 

Polices supportées:
- arial
- comic sans ms
- courier new
- cursive
- just lovely
- monospace
- serif
- times new roman
- ubuntu
- verdana
- Pour plus de polices, visitez ce site Website link: https://developer.mozilla.org/en-US/docs/Web/CSS/font-family

3.5- Watermark

Utilisez cet outil pour ajouter un filigrane à l'image

Exigences de l'outil:
- Watermark Fichier
    - Un fichier image du filigrane

- Opacité
    - Spécifiez une valeur pour l'opacité du filigrane

- Position
    - Choisissez une position pour le filigrane


4- Filtres
Il y a 4 filtres.Qui sont

- Luminosité
- Contraste
- Saturation
- Teinte

Each filter has 2 buttons, A button `+` to increase it's value and another button `-` to decrease it

5- Effects

Effects are just a combination of multiple filters with specific values

Click on an effect to apply it

6- Télécharger

Pour ouvrir le menu de téléchargement, cliquez sur le bouton de téléchargement dans le coin inférieur droit de l'éditeur

Après avoir ouvert le menu, spécifiez un "nom de fichier" et un "format de fichier"

NOTE:
- Utilisez "PNG" pour un fond transparent
- Utilisez "JPG" pour une taille de fichier plus petite

Then click on the download button

### Caractéristiques:
#### Outils:
- Crop
- Rotate
- Flip
- Text
- Watermark

#### Filtres:
- Brightness
- Contrast
- Saturation
- Vibrance

#### Effets:
- Blur
- Sepia
- Vintage
- Lomo
- Greyscale
- Clarity
- Sin City
- Cross Process
- Pinhole
- Nostalgia
- Her Majesty
- Grungy
- Orange Peel
- Love
- Jarques
- Old Boot
- Glowing Sun
- Hazy Days
- Hemingway
- Concentrate

#### Ce site prend en charge les changements de gerbage. Vous pouvez donc appliquer plusieurs effets et filtres à la même image.
### Besoin d'aide ?
Pour plus d'informations, consultez le fichier nommé "doc.html" joint dans l'archive téléchargée.
