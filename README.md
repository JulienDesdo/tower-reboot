# tower-reboot

Ce projet est une tentative de reboot d’un ancien prototype de tower defense en C++, 
initialement inspiré de Plants vs Zombies. Le jeu se déroule sur un gazon structuré en grille,
où le joueur peut placer différentes tours — réparties en trois classes — 
qui montent de niveau et produisent des unités ou de l'argent. L'argent sert à améliorer les batiments. 

Ces unités avancent automatiquement, engagent les ennemis, et interagissent dans une boucle de jeu en temps réel. 
Le prototype d’origine était assez brouillon : graphiquement très sommaire, avec plusieurs versions divergentes du code, une logique de jeu incomplète et peu de structure. 
Ce projet a donc pour but de reprendre les bases existantes & ce qui fonctionne, de nettoyer le code, et d’en faire une version stable, jouable, et correctement documentée — avec une organisation propre, un système de build simple (Makefile), et une éventuelle containerisation (Docker) pour simplifier son exécution.
