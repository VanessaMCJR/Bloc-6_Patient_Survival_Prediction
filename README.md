# Projet-final-bloc-6-Patient_-Survival-_Prediction

## Lien de la vidéo de présentation du projet:

https://share.vidyard.com/watch/6sB3nte4rewz9JrhtcVdkf?


Prédiction de la survie du patient en milieu hospitalier

Les prédicteurs de la mortalité hospitalière des patients admis restent mal caractérisés. Notre objectif est de développer et de valider un modèle de prédiction de la mortalité hospitalière toutes causes confondues chez les patients admis. 


Et ensuite de créer une application web de prédiction du risque de la mortalité destinée en premier lieu aux personnels soignants afin de faciliter une meilleure prise en charge du patient admis.

Lien de l'application : 

https://patients-survival-prediction.herokuapp.com/


Dans ce bloc on retrouve:
 - Patient_ Survival _Prediction_Bloc6_version_finale.ipynb : fichier code python (lecture dataset, EDA, machine learning) 
 
 - dataset.zip: contient le fichier dataset.csv sous forme compressée
 
 - Etude_influence_age_genre.png : image plotly de "Etude de l'influence de l'âge et du genre sur la survie en milieu hospitalier"
 
 - dossier app1 : (contient tous les fichiers de l'application web streamlit):
 
        - prediction.py (code python streamlit: application web)
        - Dockerfile : fichier qui liste les instructions à exécuter pour construire une image
        - dossier **.streamlit** contient le fichier **config.toml** qui fait le lien entre le Dockerfile et le serveur web de la plateforme heroku
        
