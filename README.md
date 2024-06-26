checkpoint-1-Algo-readSentence

#Instructions
on vous demande d'écrire un algorithme qui lit une phrase, qui se termine par un point, caractère par caractère, et de déterminer :

La longueur de la phrase (le nombre de caractères).
Le nombre de mots dans la phrase (en supposant que les mots soient séparés par un seul espace).
Le nombre de voyelles dans la phrase.

#algorithme 
1-Initialiser les compteurs : longueur = 0, mots = 0, voyelles = 0.
2-Lire le premier caractère. 
3-Tant que le caractère lu n'est pas un point : 
4-Incrémenter le compteur de longueur. 
5-Si le caractère est une voyelle (a, e, i, o, u, A, E, I, O, U), incrémenter le compteur de voyelles. 
6-Si le caractère est un espace et le caractère précédent n'est pas un espace, incrémenter le compteur de mots. 
7-Lire le caractère suivant. 
8-Ajouter 1 au compteur de mots pour le dernier mot.
9-Afficher les compteurs de longueur, de mots et de voyelles.
