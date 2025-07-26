# 🔍 Clustering de Séries Temporelles par la Méthode des Shapelets  
*Projet de fin d'études réalisé avec EDF*

---

## 🧠 Contexte et Problématique Métiers

Dans le secteur de l’énergie, la surveillance des infrastructures critiques (barrages, centrales, réseaux) repose sur l’analyse de milliers de séries temporelles issues de capteurs.  
Face à la complexité croissante des signaux collectés, il devient essentiel de disposer d’outils robustes pour :

- Identifier des **comportements anormaux ou suspects** (early warning)
- Regrouper automatiquement des profils de séries pour **prioriser l’analyse humaine**
- Diminuer les risques opérationnels liés aux **défaillances non détectées**

Ce projet s’inscrit dans une initiative portée par **EDF** pour automatiser la **détection d’anomalies** dans les mesures de hauteur d’eau de barrages hydroélectriques à partir de méthodes de **clustering non supervisé**.

---

## 🎯 Objectifs

- Implémenter une méthode innovante de **clustering basée sur les shapelets**, permettant de détecter des motifs locaux discriminants dans des séries temporelles.
- Comparer cette méthode à d’autres approches de référence (DTW, k-means, k-shape).
- Améliorer la performance algorithmique (temps de traitement, scalabilité) pour une **utilisation réelle sur données industrielles**.
- Proposer un socle de code reproductible, documenté et évolutif pour une future industrialisation chez EDF.

---

## 🧩 Ma contribution

🔬 **Approche scientifique**
- Lecture approfondie de l’article fondateur sur les shapelets.
- Reproduction fidèle de l’algorithme à partir de zéro.

💻 **Développement et optimisation**
- Implémentation complète en Python (modularisé et documenté).
- Accélération du calcul par **vectorisation** et **parallélisation** (`joblib`).

📊 **Évaluation & résultats**
- Benchmarks sur jeux de données simulés et open source (UCR archive).
- Visualisation des motifs shapelets retenus et interprétation métier.
- Mesure de la robustesse selon bruit, longueur de série et granularité.

🧾 **Rédaction**
- Rédaction d’un rapport technique détaillé pour EDF.
- Transmission des livrables pour intégration potentielle en interne.

---

## 💼 Enjeux métiers couverts

Ce type de solution peut s’appliquer à de nombreux cas d’usage à forte valeur ajoutée :

- 🔧 **Maintenance prédictive** : détection précoce de comportements inhabituels (industrie, énergie, transports)
- 💧 **Surveillance de capteurs** : regroupement de signaux similaires pour identifier des dérives ou des défauts
- 🧬 **Santé / biologie** : classification de signaux ECG, EEG ou séries métaboliques
- 📈 **Finance** : segmentation de comportements de marché (volatilité, anomalies structurelles)

---

## 🧪 Technologies utilisées

- **Python 3.10**
- NumPy, Pandas, Scikit-learn
- Matplotlib, Seaborn (visualisation)
- Joblib / Multiprocessing (parallélisation)

---

## 🏁 Résultats clés

- ✔️ Reproduction des résultats de l’article scientifique (validation théorique)
- ⚡ Temps de calcul divisé par 3 sur des jeux de données de taille moyenne
- 📌 Méthode capable d’isoler automatiquement des motifs récurrents localisés (shapelets)
- 🔍 Identification visuelle de groupes de séries anormales dans des jeux réels

---

## 👤 Auteur

**Sonokoli**  
Étudiant en dernière année à l’ENSAI — Spécialisation Data Science & Statistique Appliquée  
Projet réalisé en collaboration avec **EDF**  
Supervision : *Julien Pelamatti, Research Engineer*

---

## 📬 Contact

📧 sorobamara7@gmail.com  
📄 Rapport disponible sur demande  
🔗 [Ajoute ici ton LinkedIn ou GitHub si tu veux le partager]

---
