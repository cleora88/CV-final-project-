Dataset — License Plate Deblurring
===================================

Ce dossier contient les images d'entrée du projet.

Structure
---------
data/
    synthetic/
        sharp/      30 images de plaques nettes (PNG, 128x384 px)
        blurred/    30 images floues correspondantes (PNG, 128x384 px)

Génération
----------
Les images sont générées automatiquement par la première cellule
d'exécution du notebook (code/License_Plate_Deblurring.ipynb).

Modèle de dégradation : y = h * x + n
  - x      : image nette (plaque synthétique)
  - h      : PSF de flou de mouvement rectiligne (longueur L, angle theta)
  - n      : bruit gaussien additif (sigma = 0.005)
  - L      : tire aleatoirement dans [9, 25] pixels
  - theta  : tire aleatoirement dans [0, 180) degres

Paramètres fixes
----------------
  Taille des images : 128 x 384 pixels (hauteur x largeur)
  Nombre de paires  : 30
  Graine aleatoire  : 42 (reproductible)
  Format            : PNG (sans perte)

Données réelles
---------------
Le dossier data/real/ est prevu pour accueillir de vraies photos
de plaques floues. Il est vide car le projet repose sur des donnees
synthetiques entierement controlees (PSF et bruit connus).
