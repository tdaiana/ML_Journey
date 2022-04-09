# Prediction_am-lioration_acuite_visuelle_apres_une_chirurgie_trou_maculaire
A partir d’exemples de chirurgie, prédire dans quelle mesure l’opération aura un impact positif sur l’acuité visuelle du patient.
Nous avons abordé le problème en utilisant une technique d’apprentissage non supervisé, c’est-à-dire en utilisant l’analyse en composantes principales(ACP) et les algorithmes supervise plus précisément la régression linéaire. 

Dans le cas de la détection de changement après l’intervention, l’apprentissage supervisé prendra les images et les données préopératoires pour prédire les changements dans l’acuité visuelle du patient après 6 mois de l’intervention. 

References Godbout, M., et al. "Predicting Visual Improvement after Macular Hole Surgery: a Cautionary Tale on Deep Learning with Very Limited Data." arXiv preprint arXiv:2109.09463 (2021). https://arxiv.org/pdf/2109.09463v2.pdf

1.3.1  Context
Les données représentent des chirurgies de trous maculaires réussies de 2014 à 2018 au CHU de Québec.

Nous sommes intéressés à savoir si nous pouvons, à partir d’exemples de chirurgie, prédire dans quelle mesure l’opération aura un impact positif sur l’acuité visuelle du patient.

Predire les valeurs de l’acuité visuelle du patient apres 2 semains de l'operation, 3 mois, 6 mois respectivement 12 mois.

https://www.kaggle.com/mathieugodbout/oct-postsurgery-visual-improvement