#H1 Calcul des bâtons en SVG

#H2 Pour calculer le graphique en bâton, il faut :

-détérminer la hauteur et la largeur de la zone de dessin

-créer un rectangle coloré pour le fond du graphique _(optionnel)_

-créer un tableau de bâtons avec la fonction .map qui prend en paramètre les objets et un index.
-on multiplie l'index avec la largeur des bâtons, ce qui nous donne la valeur x pour chaque bâton
-on soustrait la hauteur du graphique avec le numéro de l'objet bâton, ce qui nous donne la valeur y pour chaque bâton
-la largeur des bâtons est donnée par la variable du début
-la hauteur des bâtons est donnée par la valeur correspondante dans l'objet fruit

on peut ajouter du texte mais ce n'est pas obligatoire