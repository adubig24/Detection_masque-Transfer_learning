# Création d'un modèle de détection de masques via Transfer Learning

Ce brief a pour objectif d’appliquer le Transfer Learning sur une base de données.

Dans ce brief, nous appliquons un apprentissage supervisé pour identifier si la personne porte un masque ou non.

# Utilisation

Nous avons utilisé les ressources de Google Colab via un notebook utilisant ses ressources.
Le fichier .ipynb est à importer dans google collab, et les dossiers Mask_Data_test et Mask_Data_train sont dans un dossier Mask_Data dans un google drive.
Le notebook enregistre en sortie le meilleur modèle, qu'il faut ensuite télécharger avec use_model.py afin de tester la détection en direct avec la webcam.

# Modèle utilisé

Le modèle utilisé était au début VGG16, puis nous avons bifurqué sur InceptionResNetV2 qui est plus précis que ce dernier. C'est donc celui utilisé à la fin.
Nous avons également montré des graphiques pour montrer l'évolution de l'entrainement, ainsi qu'une matrice de corrélation et un test avec des images tirées du net dans le notebook pour tester et évaluer le modèle.