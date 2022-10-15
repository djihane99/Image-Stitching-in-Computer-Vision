# Image-Stitching-in-Computer-Vision

L'objectif de ce travail est d'implémenter un algorithme nous permettant de créer une mosaïque d'images.
Une mosaïque combine plusieurs images ayant des champs de vue se chevauchant afin de produire un panorama.

![exo22](https://user-images.githubusercontent.com/68650014/195990183-b28a83b9-5d2e-4e60-b31e-2e9cb5244204.PNG)

Dans un premier temps, nous ferons le recalage (appariement des caractéristiques similaires dans les différentes images afin de transformer des ensembles différents de données dans un seul système de coordonnées). Ensuite, nous aurons à développer une méthode de détection de points d'intérêt et d'appariement automatiques.
Dans Matlab et Python, il existe déjà des fonctions effectuant en grande partie la tâche.

Et voilà ce qu'on obtiendrons comme résultat:

![exo21](https://user-images.githubusercontent.com/68650014/195990291-771b9362-c175-464a-ade0-6cb3e959c56d.PNG)

Cet exemple vous a montré comment créer automatiquement un panorama à l'aide de techniques d'images basées features. Des techniques supplémentaires peuvent être incorporées dans l'exemple pour améliorer le mélange et l'alignement des images panoramiques
