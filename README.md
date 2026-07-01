# 🏆 Coupe du Monde 2026 — Gestion des scores

Application web en HTML/CSS/JavaScript pour suivre et gérer les scores de la **Coupe du Monde FIFA 2026**.

## Fonctionnalités

- Saisie manuelle des scores pour chaque match de la phase de groupes
- Calcul automatique des points (3 pts victoire, 1 pt nul, 0 pt défaite)
- Classement automatique des équipes dans chaque poule (par points, différence de buts, buts marqués)
- Mise en évidence des 2 équipes qualifiées par groupe
- Tableau à élimination directe (1/16 → 1/8 → 1/4 → 1/2 → Finale + Petite finale)
- Propagation automatique des vainqueurs dans le bracket
- Sauvegarde persistante dans le `localStorage` du navigateur (les scores ne disparaissent pas au rafraîchissement)
- Export / Import des scores au format JSON
- Réinitialisation complète des scores

## Structure du projet

```
World-cup-2k26/
├── coupe_du_monde_2026.html   # Application principale (fichier unique)
├── scores_cdm2026.json        # Exemple de scores de la phase de groupes
└── README.md                  # Ce fichier
```

## Utilisation

1. Ouvrir `coupe_du_monde_2026.html` directement dans un navigateur (aucun serveur requis)
2. Saisir les scores de chaque match dans les cases prévues
3. Les classements et le tableau se mettent à jour en temps réel
4. Pour sauvegarder une copie des scores, cliquer sur **Exporter (JSON)**
5. Pour restaurer des scores sauvegardés, cliquer sur **Importer (JSON)**

## Données incluses

Le fichier `scores_cdm2026.json` contient un exemple de scores pour la **phase de qualification par groupes** (Groupes A à L). Ces données peuvent être importées directement dans l'application via le bouton **Importer (JSON)**.

## Technologies

- HTML5 / CSS3 / JavaScript (vanilla, aucune dépendance)
- `localStorage` pour la persistance des données

## Groupes

| Groupe | Équipes |
|--------|---------|
| A | Mexique, Afrique du Sud, Corée du Sud, République tchèque |
| B | Canada, Bosnie-Herzégovine, Qatar, Suisse |
| C | Brésil, Maroc, Haïti, Écosse |
| D | États-Unis, Paraguay, Australie, Turquie |
| E | Allemagne, Curaçao, Côte d'Ivoire, Équateur |
| F | Pays-Bas, Japon, Suède, Tunisie |
| G | Belgique, Égypte, Iran, Nouvelle-Zélande |
| H | Espagne, Cap-Vert, Arabie Saoudite, Uruguay |
| I | France, Sénégal, Irak, Norvège |
| J | Argentine, Algérie, Autriche, Jordanie |
| K | Portugal, RD Congo, Ouzbékistan, Colombie |
| L | Angleterre, Croatie, Ghana, Panama |
