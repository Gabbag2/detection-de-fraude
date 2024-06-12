# Challe de detection-de-fraude

Le but de ce challenge est d'identifer la probabilité qu'un client soit fraudeur ou non. 

Le panier se décompose au maximum en 24 items. Par exemple, si un panier contient 3 items alors toutes les informations relatives à ces 3 items seront renseignées dans les colonnes item1, item2, item3, cash_price1, cash_price_2, cash_price3, make1, make2, make3, model1, model2, model3, goods_code1, goods_code2, goods_code3, Nbr_of_prod_purchas1, Nbr_of_prod_purchas2 et Nbr_of_prod_purchas3. Les variables restantes (celles avec un indice > 3) seront vides .

Un item correspond à un produit ou un regroupement de produits équivalents. Par exemple, si un panier contient 3 Iphones 14, alors ces 3 produits seront regroupés dans un seul item. Par contre, si le client achète 3 produits Iphone différents, alors nous considèrerons ici 3 items.

Pour chaque observation de la base, il y a 147 colonnes dont 144 peuvent être regroupées en 6 catégories :

item, cash_price, make, model, goods_code, Nbr_of_prod_purchas.

Taille : 115 988 observations, 147 colonnes.

Distribution de Y :

Fraude (Y=1) : 1 681 observations

Non Fraude (Y=0) : 114 307 observations

Le taux de fraude sur l'ensemble de la base est autour de 1.4%.

La métrique utilisé est l'aire sous la courbe Précision-Rappel.

Le code fourni est notre solution pour le data challenge 
