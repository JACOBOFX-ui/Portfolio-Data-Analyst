# Projet 2 — Screener / détecteur d'opportunités boursières
**Étape 2 du pipeline : FILTRER** *(nom technique : StockDB)*

---

## 1. Brief client (simulé)

> "Je suis une trentaine d'actions pour repérer les bonnes opportunités, mais je passe des heures chaque semaine à vérifier une par une si l'une d'elles est devenue intéressante — un P/E qui a baissé, un dividende correct, une bonne dynamique récente. Je voudrais que ce tri se fasse tout seul."

**Profil client type :** investisseur particulier actif suivant un portefeuille élargi, ou petit cabinet indépendant qui présélectionne des titres pour ses clients.

---

## 2. Cadrage

- Reformulation du besoin : automatiser un filtrage répétitif, pas remplacer le jugement du client
- Questions validées avant développement : quels critères de filtrage (P/E, dividende, momentum sectoriel...), quelle fréquence de mise à jour, quel format de restitution
- Rappel : un screener oriente, il ne décide pas à la place du client

---

## 3. Collecte / préparation des données

**Même entrepôt de données que le Projet 1** — c'est le point clé qui prouve la cohérence du pipeline plutôt que 4 outils isolés :
