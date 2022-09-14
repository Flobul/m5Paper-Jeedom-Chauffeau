# m5Paper-Jeedom-Chauffeau
## Utilisation de code Blocky via UIFlow 

Le M5Paper est une tablette ESP32 équipée d'un écran tactile ePaper (ultra basse consommation).
Jeedom est un serveur domotique compatible avec de nombreaux protocoles.

But du code :
- afficher la température actuelle du ballon, récupérée via requête GET http avec clé api jeedom, (Réalisé)
- afficher un graphique sur 24 heures de la température de la sonde de température située dans le ballon chauffe-eau, (Réalisé)
- afficher 3 boutons en bas de page indiquant l'état actuel du plugin Chauffeau de Jeedom (pour rappel, le plugin Chauffeau calcul le temps nécessaire à la montée en température de consigne de l'eau par le ballon tout en prenant en compte les HP/HC). (Réalisé)
- rendre le bouton de changer d'état du plugin Chauffeau clicable afin de déclencher une chauffe de l'eau. (à faire)
