Une page existe pour afficher la météo, cette page affiche des données en dur,
le but du test est de récupérer les données d'une l'API coté back et de les insérer dans la vue,

Ressource :
1/ Utiliser l’API Json suivant :
https://raw.githubusercontent.com/kang-fr/weather_api/main/last.json

Règles pour la température :
- Il faut convertir les Kelvin en degrés Celsius, et arrondir à l’entier
- La température sur la journée est la température maximale et minimale
- La température en gras est la température maximale sur le journée

Règles pour le picto Soleil/Nuageux/Pluie :
< 20 = Soleil
entre 20 et 50 = nuageux
Plus de 50 = pluie

Pour le jour en cours, afficher la valeur de l'heure en cours (temperature & pluie)
Pour les jours suivant, pour le picto Soleil/Nuageux/Pluie prendre la moyenne sur la journée
