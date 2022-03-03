# Prediction-Maladie
Projet de Stage

## À Propos

Cette application Web a été développée à l'aide de Flask et a été déployée sur le serveur Heroku. Les modèles utilisés pour prédire les maladies ont été entraînés sur de grands ensembles de données. Tous les liens pour les ensembles de données et les cahiers python utilisés pour la création de modèles sont mentionnés ci-dessous dans ce fichier readme. L'application Web peut prédire les maladies suivantes :

- Diabète
- Cancer du sein
- Cardiopathie
- Maladie du rein
- Maladie du foie
- Paludisme
- Pneumonie

## Modèles avec leur précision de prédiction

| Maladie         | Type de Modèle           | Accuracy |
| --------------  | ------------------------ | -------- |
| Diabète         | Machine Learning Model   | 98.25%   |
| Cancer du sein  | Machine Learning Model   | 98.25%   |
| Cardiopathie    | Machine Learning Model   | 85.25%   |
| Maladie reinale | Machine Learning Model   | 99%      |
| Maladie du foie | Machine Learning Model   | 78%      |
| Paludisme       | Deep Learning Model(CNN) | 96%      |
| Pneumonie       | Deep Learning Model(CNN) | 95%      |

## NOTE

==> Vous pouvez accéder au site ici : ? <br>
==> Vous pouvez trouver tous les modèles dans [models](https://github.com/skyclanlourro/Prediction-Maladie/tree/master/models) folder.

## Étapes pour exécuter cette application dans votre système

1. Clonez ou téléchargez le repo.
2. Ouvrez l'invite de commande dans le dossier téléchargé.
3. Créer un environnement virtuel

```
mkvirtualenv environment_nom
```

4. Installez toutes les dépendances :

```
pip install -r requirements.txt
```

5. Lancez l'application

```
python app.py
```

## Liens Datasets

Tous les jeux de données ont été utilisés à partir de kaggle.

- [Dataset Cardiopathie](https://www.kaggle.com/ronitf/heart-disease-uci)
- [Dataset Diabète](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- [Maladie Reinale Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
- [Maladie du Foie Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
- [Paludisme Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
- [Pneumonie Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- [Cancer du Sein Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

## Liens pour les notebooks utilisés pour la création des modèles

- [Diabète Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Diabetes_Prediction.ipynb)
- [Cancer du Sein Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Cancer_Prediction.ipynb)
- [Cardiopathie Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
- [Maladie Reinale Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
- [Maladie du Foie Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)

# Auteur

[Nyam](https://github.com/skyclanlourro)
