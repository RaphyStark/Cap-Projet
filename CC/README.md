CC_V1 : Implémentation d’interruptions pour récupérer les valeurs des encodeurs

CC_V2 :  Utilisation de la librairie PID_v1

CC_V3 :  Utilisation de la librairie Encoder qui remplace l’implémentation des interruptions, librairie PID _v2

CC_V4 :  Utilisation des neopixels, librairie FastPID remplace la librairie PID_2, implémentation fonction rotate, forward, arrêt

CC_V5 :  Retour sur la librairie PID_v2, stockage des coordonnées dans un tableau et implémentation de la fonction nextPoint pour passer d’un couple de coordonnées (x,y) à un autre

CC_V7 :  Les tableaux sont bien pour du rectiligne => essai d’utilisation de PID_v2 sans tableaux et une distance en cm comme condition d’arrêt 

CC_V8 :  Implémentation de notre propre correcteur proportionnel et un temps calculé par millis() comme condition d'arrêt

CC_V9 :  Ajout de la variable newTime pour laisse le temps au correcteur de faire effet avant de recalculer l'output (newTime trop grand à ce moment)

CC_V10 : Ajout de la fonction neopixel pour plus de clareté

CC_V12 : Implémentation des correcteurs intégral et dérivé et de la fonction wait qui remplace delay

CC_V13 : Implémentation de la fonction initialize qui tune le coefficient en fonction de la consigne. La consigne est comprise entre 0 et 120 en valeur absolue
