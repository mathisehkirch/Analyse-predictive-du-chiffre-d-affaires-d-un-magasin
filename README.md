# Projet de Prédiction des Ventes en Magasin

## Objectif
Le projet vise à utiliser la prévision de séries temporelles pour prédire les ventes en magasin à partir des données de Corporación Favorita, une grande chaîne d'épiceries basée en Équateur.

## Dataset
Nous avons utilisé le jeu de données fourni par Kaggle, comprenant des informations sur les dates, les magasins, les articles, les promotions et les ventes unitaires. Des données concernant les métadonnées des magasins, le prix quotidien du pétrole et les vacances y sont aussi inclus. Ces jeux de données nous ont permis de pratiquer nos compétences en apprentissage automatique avec un ensemble de données accessible.

Lien : [Dataset Kaggle](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview)

## Résultats
Après avoir développé notre modèle en interne sans recourir à du code externe, nous avons obtenu des résultats prometteurs sur l'échantillon de test de Kaggle, avec un score final de ~0.5. Ci-dessous une capture d'écran de notre classement sur Kaggle :

<img width="1127" alt="Screenshot 2024-04-27 at 23 00 06" src="https://github.com/mathisehkirch/projetml/assets/161879747/f5975e05-3bf6-489a-9ecf-a18db3c97482">

## Utilisation de l'application
Une application streamlit devrait démarrer localement après l'exécution du script Python. Ouvrez l'application avec le lien créé dans la dernière cellule du script. Utilisez votre "URL externe" au format '12.123.123.123', trouvée dans le fichier /logs.txt créé dans votre environnement lors de l'exécution du script, comme mot de passe pour streamlit. Téléchargez vos données pour une prédiction en utilisant notre modèle.

##
Membres du groupe : EHKIRCH Mathis ALLAM Simon

Licence du projet : Ce projet est publié sous licence GNU GPL, ce qui signifie qu'il est open-source et que quiconque peut accéder au code source, le modifier et le redistribuer sous certaines conditions.
