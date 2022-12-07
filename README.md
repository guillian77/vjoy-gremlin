# vjoy-gremlin

## Périhérique virtuel
1. Installer vJoy
2. Configurer un joystick virtuel
    - Mettre le nombre de boutons, les axes, les chapeaux, etc..
    - Exemple : 
        - Si configuration avec 2 Thrustmaster T16000.
        - Alors, 1 T16000 = 16 boutons
        - Donc, configurger 32 boutons sur le joystick virtuel (c'est le nombre maximum pour StarCitizen)
        - Sélectionner les axes X,Y,Z et X,X,Z rotation. Il seront répartie entre les deux joystick physique.
    - Cliquer sur "Apply".
    - Cocher "Active vJoy".
    - Plus besoin de toucher vJoy, il ajoutera en permanance ce joystick virtuelle.

## Configurer le joystick virtuel (bind T1600 -> vJoy)
1. Installer Gremlin
2. Gremlin doit repérer les périphériques physique à gauche et le virtuel à droite.
3. Si ce n'est pas le cas. Débrancher/Brancher un périphérique physique. Voir redémarrer le PC.
4. Bind les touches des périphériques physique vers le périphériques virtuel.
5. Enregistrer précieusement le profil.
6. Activer la configuration via l'icône de la manette.
7. Tester la configuration via l'analyseur.

## Masquer les périphériques physiques
1. Permet d'éviter que StarCitizen continue de visualiser les périphériques physique.
2. StarCitizen ne peut prendre en charge qu'un seul Joystick/HOTAS.
3. StarCitizen prendra le premier joystick trouvé !
4. Le but est de faire en sorte que cela soit le joystick virtuel qui soit détecté en premier.
5. C'est pour cela qu'on va cacher les périphériques physique à StarCitizen.
6. Installer HidGuardian via l'installeur WhiteKnight.
7. Redémarrer Gremlin en mode administrateur.
8. Setting -> Hidden -> Sélectionner les périphérique.
9. Vérifier que les périphériques physique ne soit plus visible par windows via le "contrôleur de jeu".
10. Si ce n'est pas le cas : redémarrer Gremlin/Rebrancher un périphérique physique.

## Remarque
Contrairement aux logiciels comme T.A.R.G.E.T, il n'est pas nécessaire de lancer absolument Gremlin avant StarCitizen.
L'activation du profil dans Gremlin peut être fait après le lancement du jeu puisque StarCitizen à déjà détecté le joystick
virtuel qui lui reste en permanance connecté.
Ce qui donne un autre avantage : le périphérique virtuelle peut être modifié à la vôlé pendant que le jeu est ouvert !
Changement de courbes, rebind d'axes, de touches, etc.

## Conclusion
Un logiciel comme T.A.R.G.E.T offre un interface PARFOIS plus simple et un peu plus smooth, mais quand vous
aurez goûté au bonus de Gremlin qui vous permettra de ne plus vous prendre la tête à savoir si vous avez
bien lancé votre profil ou si vous voulez fusionner des périphériques entre eux (exemple : les axes de pédales).
Vous ne voudriez plus revenir en arrière.

## Enjoy!
