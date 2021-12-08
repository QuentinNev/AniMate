# Projet AWA1 : AniMate - Animation d'un personnage

Le but de ce projet est d'animer un personnage dans Unity 3D en utilisant toutes les technologies disponibles (Animation & Tree blending, animation layer, Inverse Cinematic) afin d'avoir un rendu final fluide.

## Technologies

- Unity 2020
- C#

## Fonctionnalités

### Character controller

Afin de rendre l'expérience ludique et de facilement pouvoir tester les limites du système d'animation, il sera possible de contrôler le personnage à la manette ou au clavier + souris.

- Marcher (En avant, arrière, gauche, droite)
- Courir (En avant, légèrement à gauche ou à droite)
- Sauter

### Animation

L'animation aura plusieurs état principaux :

- Idle (ne bouge pas)
- Walk (avancer lentement)
- Run (avancer rapidement)

Un premier blend d'animation sera fait entre ces 3 différents états, en fonction de la vitesse du personnage. Par exemple à une vitesse maximal de 10, l'animation Run prendra 100% du blend, à 5 l'animation Walk sera à 100% et à 0 ce sera Idle à 100% à 7.5 ce sera un blend entre Walk et Run, les deux à 50%.