# 🕵️‍♀️ Détecteur de SPAM AT&T

## 📇 Description de l'entreprise

**AT&T Inc.** est une entreprise multinationale américaine de télécommunications dont le siège est situé à Whitacre Tower, dans le centre-ville de Dallas, Texas. C'est la plus grande entreprise de télécommunications au monde en termes de revenus et le troisième plus grand fournisseur de services de téléphonie mobile aux États-Unis. En 2022, AT&T se classait au 13e rang du classement Fortune 500 des plus grandes entreprises américaines avec des revenus de 168,8 milliards de dollars ! 😮

---

## 🚧 Projet

Un des principaux problèmes auxquels les utilisateurs d'AT&T sont confrontés est l'exposition constante aux messages SPAM.

AT&T a été en mesure de signaler manuellement les messages SPAM pendant un certain temps, mais elle cherche maintenant à automatiser la détection des SPAMs pour protéger ses utilisateurs.

---

## 🎯 Objectifs

L'objectif est de créer un détecteur de SPAM, capable de signaler automatiquement les SPAMs en se basant uniquement sur le contenu des SMS.

---

## 🖼️ Portée du projet

Pour commencer, AT&T souhaite que vous utilisiez le dataset suivant :

- **[AT&T Dataset](#)**

---

## 📬 Livrable

Pour compléter ce projet, votre équipe doit :

1. Écrire un notebook qui exécute le prétraitement et entraîne un ou plusieurs modèles de deep learning afin de prédire la nature SPAM ou non (ham) du SMS.
2. Indiquer clairement les performances obtenues.

---

## Étapes de Réalisation

1. **Prétraitement des Données**
   - **Nettoyage** : Supprimer les caractères inutiles, convertir le texte en minuscules et tokeniser.
   - **Encodage des Étiquettes** : Convertir les étiquettes SPAM/ham en valeurs numériques.

2. **Développement du Modèle**
   - **Modèle de Base** : Réseau de neurones simple.

3. **Évaluation**
   - Utilisation de métriques telles que l'accuracy, le score F1, la précision et le recall pour évaluer l'efficacité du modèle.

4. **Optimisation**
   - Ajuster les hyperparamètres et expérimentez différentes architectures de modèles pour améliorer les performances.

### Résultats Attendus

- Un modèle de deep learning entraîné capable de détecter et signaler efficacement les messages SPAM en fonction du contenu des SMS.

