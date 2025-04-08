# LifeMonit

## 🎯 Objectif du projet

**LifeMonit** est une application de gestion du temps conçue pour expérimenter et démontrer plusieurs compétences techniques clés dans le cadre de ma formation en Data & Développement.

Ce projet a plusieurs objectifs :
- **Développer une application web complète** avec une structure propre et évolutive.
- **Intégrer des services AWS** pour la gestion des notifications, du stockage cloud, de la surveillance des performances, etc.
- **Mettre en œuvre des fonctionnalités d’analyse de performance**, à partir des données saisies par l’utilisateur (temps passé, fréquence, complétion…).
- **Travailler l’esthétique et l’ergonomie** pour proposer une expérience utilisateur fluide, agréable et personnalisée.

> Ce projet est développé seule, selon une méthode agile, et constitue un support d’apprentissage, d’expérimentation et de valorisation de mon profil.

---

## Méthodologie

- Méthode : **Agile simplifiée (solo dev)**.
- Organisation par **sprints courts** (1 semaine).
- Chaque sprint se concentre sur un lot de fonctionnalités minimales et testables.
- MVP en cours : **Gestion basique des tâches.**

---

## Sprint 1 – Objectif

Créer une version simple de l'application permettant :

- [ ] Ajouter une tâche
- [ ] Afficher les tâches du jour
- [ ] Marquer une tâche comme terminée
- [ ] Supprimer une tâche

---

## ⚙️ Stack technique prévue

| Côté           | Technologie               | Statut actuel    |
|----------------|---------------------------|------------------|
| Front-end      | React.js                  | 🟢 En cours      |
| Back-end       | Flask (API REST)          | ⚪ Prévu         |
| Base de données| SQLite                    | ⚪ Prévu         |
| UI Library     | (optionnel) Material UI   | 🔵 Non démarré   |
| Hébergement    | Vercel / Render           | ⚪ Prévu         |

> Le Sprint 1 fonctionne sans back-end ni base de données : les données sont stockées en mémoire localement via `useState`.


> Le Sprint 1 fonctionne sans back-end : les tâches sont stockées en local (`useState` dans React).

---

## Structure du projet (prévisionnelle)

```
life-monit/ 
├── src/
│   ├── App.js
│   ├── components/
│   │   ├── TaskForm.js
│   │   └── TaskList.js
│   └── styles/
├── public/
│   └── index.html
├── package.json
└── README.md
```
---

## Backlog global (vue future)

| Fonctionnalité                          | Priorité | Sprint prévisionnel |
|----------------------------------------|----------|----------------------|
| Rappels / Notifications                | Haute    | Sprint 2             |
| Vue calendrier                         | Moyenne  | Sprint 2/3           |
| Statistiques de productivité           | Moyenne  | Sprint 3+            |
| Synchronisation Cloud                  | Basse    | Sprint 3+            |
| Paramètres (mode sombre, etc.)         | Moyenne  | Sprint 3+            |

---

## Notes personnelles
- Ce projet est également un support de portfolio et d'entraînement personnel à la gestion de projet agile.
- L’évolution du projet sera visible au fil des commits, avec une documentation continue.

---

## Auteur
Développé par [Togji TAGBIA-LOUEVIE](https://www.linkedin.com/in/togji-tagbia-louevie-913608167/)
