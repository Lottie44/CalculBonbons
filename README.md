# CalculBonbons

Début CalculBonbons (réel argent, réel prix)

    Si argent = 0 OU prix = 0
        retourner 0
    Fin Si
    nbBonbons = 0
    Tant que nbBonbons * prix <= argent
        nbBonbons <- nbBonbons + 1
    Fin Tant que
    retourner nbBonbons - 1
    
Fin CalculBonbons
