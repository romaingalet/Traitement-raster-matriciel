# Calcul d'intersection (version matricielle)
## une alternative à l'intersection vectorielle de `GeoDataFrame` de la librairie `geopandas`.

### A - Raster_overlay
Ici, le raster résultant est obtenu par une somme de matrices.

Deux couches:
- (1) Une segmentation de l'espace (~pyr)
- (2) Une classification (~ocs)

La matrice pivot finale donne la répartition des classes (1) sur chaque entité de la segmentation (2).

### B - Vectorisation (numpy array -> shp & tif -> shp)
Code minimal, Gestion CRS, Solution la plus compacte
![image](https://github.com/romaingalet/Traitement-raster-matriciel/assets/87038114/ceb1926a-6799-4ddc-8c68-fbce98c383a2)

