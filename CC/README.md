CC_V1 : implémentation d’interruptions pour récupérer les valeurs des encodeurs
CC_V2 : utilisation de la librairie PID_v1
CC_V3 : utilisation de la librairie Encoder qui remplace l’implémentation des interruptions, librairie PID _v2
CC_V4 : utilisation des neopixels, librairie FastPID remplace la librairie PID_2, implémentation fonction rotate, forward, arrêt
CC_V5 : retour sur la librairie PID_v2, stockage des coordonnées dans un tableau et implémentation de la fonction nextPoint pour passer d’un couple de coordonnées (x,y) à un autre
CC_V7 : les tableaux sont bien pour du rectiligne => essai d’utilisation de PID_v2 sans tableaux et une distance en cm comme condition d’arrêt 
CC_V8 :  implémentation de notre propose correcteur (que proportionnel) CC_V9 :  ajout de la variable newTime pour laisse le temps au correcteur de faire effet avant de recalculer l'output (newTime trop grand à ce moment)
CC_V10 :  ajout de la fonction neopixel pour plus de clareté
CC_V12 :  implémentation des correcteurs intégral et dérivé et de la fonction wait pour remplacer delay
CC_V13 : tunage du PID en fonction de la consigne, amélioration du printInfo() en debug()
