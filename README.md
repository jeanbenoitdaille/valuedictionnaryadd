# valuedictionnaryadd
Aditionner une valeur dans un dictionnaire 
Pour récupérer toutes les valeurs d'un dictionnaire, on peut utiliser la méthode values :

    >>> employes.values()
    dict_values([2500, 5000, 1200])

Et pour obtenir la somme de toutes ces valeurs, rien de plus simple que d'utiliser la fonction sum :

    >>> sum(employes.values())
    8700
