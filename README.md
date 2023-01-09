# Projet_6_Moteur_de_classification
L'objectif de ce projet de formation est de réaliser une première étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article lors de l'ajout à la marketplace par le vendeur.
Pour cela, il faut analyser le jeu de données en réalisant un prétraitement des descriptions des produits et des images, une réduction de dimension, puis un clustering.

Les résultats de la réduction de dimension et du clustering seront à présenter sous la forme de graphiques en deux dimensions, et confirmés par un calcul de similarité entre les catégories réelles et les clusters. Ces résultats illustreront le fait que les caractéristiques extraites permettent de regrouper des produits de même catégorie.

Ainsi, nous serons en mesure de démontrer, par cette approche de modélisation, la faisabilité de regrouper automatiquement des produits de même catégorie.

Contraintes :

    Afin d’extraire les features texte, il sera nécessaire de mettre en œuvre :
        deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf ;
        une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
        une approche de type word/sentence embedding avec BERT ;
        une approche de type word/sentence embedding avec USE (Universal Sentence Encoder).

    Afin d’extraire les features image, il sera nécessaire de mettre en œuvre :
        un algorithme de type SIFT / ORB / SURF ;
        un algorithme de type CNN Transfer Learning
