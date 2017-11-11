Il s’agit d’un WPS qui contient deux méthodes, la première prend en entrée
une géométrie, récupères ces coordonnées et les modifie (décale X et Y de
chaque coordonnée) et renvoie une nouvelle géométrie avec les nouvelles
coordonnées. La deuxième, elle prend en entrée une FeatureCollection,
récupère les coordonnées de chacune des géometrie de contenue dans cette
dernière, fait la même chose que la première méthode et renvoie une
FeatureCollection avec les nouvelles géométries obtenues après modification.
La troisième prend en entrée une FeatureCollection qui contient des
géométries de type LineString, elle permet de pivoter les coordonnées de
chacune de ces dernières et renvoi en sortie une FeatureCollection avec les
nouvelles géométries obtenues après modification.
