# CalculBonbons

Début CalculBonbons (réel argent, réel prix)

    nbBonbons <- 0
    Si argent > 0 ET prix > 0
        Tant que nbBonbons * prix <= argent
            nbBonbons <- nbBonbons + 1
        Fin Tant que
        retourner nbBonbons - 1
    Fin Si
    retourner nbBonbons
    
Fin CalculBonbons
