# Projet-RPG-Textuel-Java
Dans mon projet, il y a 4 package:
  - game qui contient le main, le map
      - le main c'est le coeur du RPG, j'appele ici mes méthodes pour faire vivre le jeu
      - le map est la carte du jeu je place ici le joueur position fixe(en bas à gauche) et les obstacle, monstres et destination finale position aléatoire et j'mplémentes des méthodes pour que le joueur réagissent différemment selon ce qu'il     rencontre.
    
    
  - weapons contenant les classes Weapon, WeaponShop, Bow, Sword et Axe
      - les classes Bow, Sword et Axe assigne respectivement les noms(Bow, Sword et Axe), dommages infligés par l'arme et la representation ASCII de l'arme
      - la classe weapons contien le constructeur de chaque arme
      - et la classe weaponshop permet de display les armes et acheter
        
  - monstre_obstacles contenant les classes Destructible, Obstacle et Monstre
      - la classe Destructible contien le constructeur pour les dégats reçus et infligé ainsi que la vie(envie ou pas) des monstres et obstacles
      - la classe Obstacle initialise les hp perdu face à un obstacle
      - la classe Monster initialise les hp perdu face à un monstre
        
  - et enfin player qui contient les classes Players, ActionPlayer, Sorcerer, Human et Elf
      - la classe Player contient le constructeur d'un joueur
      - les classes Sorcerer, Human et Elf sont des types de joueurs et ont des hp(points de vie) différents selon leur types
      - et la classe ActionPlayer contient toutes les actions qu'un joueur peut effectuer(se déplacer, choisire une arme,...)
