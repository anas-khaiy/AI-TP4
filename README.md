# Projet K-Means Clustering

Ce projet explore l'application de l'algorithme de clustering **K-Means** sur le jeu de données Iris.

## Étapes principales

### 1. Chargement des données
*   Utilisation du dataset **Iris** (via scikit-learn).
*   Affichage des 5 premières lignes pour identifier les variables (sepal/petal length/width).

### 2. Prétraitement
*   **Nettoyage** : Vérification des valeurs manquantes (aucune détectée).
*   **Normalisation** : Mise en échelle des données avec `StandardScaler` pour uniformiser les variables.

### 3. Visualisation exploratoire
*   Réalisation de graphiques 2D (scatter plots).
*   Identification visuelle de groupes distincts, particulièrement sur les dimensions des pétales.

### 4. Application de K-Means
*   Configuration de l'algorithme avec **k = 3** clusters.
*   Exécution avec `KMeans` de scikit-learn.
*   Exportation des centres (centroïdes) et des labels pour chaque point.

### 5. Évaluation
*   Graphique final montrant les clusters colorés et leurs centres.
*   Calcul du **Silhouette Score** : obtenu environ **0.48** pour 3 clusters.

### 6. Expérimentations
*   **Variation de k** : Test de décomposition de 2 à 6 clusters (k=2 offre la meilleure séparation mathématique).
*   **Impact de la normalisation** : Comparaison des scores de silhouette avant et après mise à l'échelle.


