# Space Invader
	## Importation des bibliothèques :
import tkinter as tk
import time
import json
	tkinter est une bibliothèque Python pour créer des interfaces graphiques.
	time est une bibliothèque Python pour accéder à l'heure et au temps.
	json est une bibliothèque Python pour travailler avec des données JSON.
	## Classe SpaceInvaders :
	C'est la classe principale du jeu. Elle contient les méthodes pour initialiser le jeu et lancer le jeu lui-même.
	Méthode __init__(self) : Initialise les variables et crée la fenêtre principale du jeu.
	Méthode play(self) : C'est la méthode principale pour lancer le jeu. Elle crée la boucle de jeu principale.
	## Classe Defender :
	Représente le défenseur du jeu.
	Contient des méthodes pour le déplacer et récupérer sa taille.
	## Classe Alien :
	Représente un alien du jeu.
	Contient des méthodes pour initialiser les aliens, les déplacer et vérifier s'ils sont touchés.
	## Classe Fleet :
	Gère la flotte d'aliens.
	Contient des méthodes pour initialiser la flotte, la déplacer et vérifier s'il y a une collision.
	## Classe Bullet :
	Représente les balles tirées par le défenseur ou les aliens.
	Contient des méthodes pour initialiser les balles et les déplacer.
	##Classe LesBunckers :
	Gère les bunkers (abris) dans le jeu.
	Contient des méthodes pour initialiser les bunkers, vérifier s'ils sont touchés par les aliens ou les balles, et mettre à jour leur état.
	## Classe Buncker :
	Représente un bunker individuel.
	Contient des méthodes pour initialiser le bunker et mettre à jour son état en fonction des dommages subis.
	## Classe Score :
	Représente le score du joueur.
	Contient des méthodes pour mettre à jour le score en fonction du temps écoulé et pour enregistrer/charger le score à partir d'un fichier.
	## Classe Resultats :
Représente les résultats (scores) du jeu.
Contient des méthodes pour ajouter un score, afficher les résultats et enregistrer/charger les résultats à partir d'un fichier.
Dans la méthode play de la classe SpaceInvaders, le jeu est lancé. La fenêtre du jeu est créée, et les différentes parties du jeu (défenseur, aliens, bunkers, score) sont initialisées. Le jeu continue à fonctionner tant que le défenseur est en vie et que la flotte d'aliens n'a pas atteint le bas de l'écran.