# PIC — Suivi des dossiers

Dashboard de suivi des projets d'accompagnement IC.

## 🚀 Mise en place (une seule fois)

1. **Créer un repo GitHub** : aller sur [github.com/new](https://github.com/new), nommer le repo (ex: `pic-dashboard`), cocher **Public**
2. **Uploader les fichiers** : glisser `index.html` et `data.csv` dans le repo
3. **Activer GitHub Pages** : Settings → Pages → Source: **Deploy from a branch** → Branch: `main` → dossier `/ (root)` → Save
4. **Attendre ~2 min** : votre dashboard est en ligne à `https://VOTRE-USERNAME.github.io/pic-dashboard/`

## 📊 Mise à jour hebdomadaire (2 minutes)

1. Exporter votre CSV depuis votre outil de gestion
2. Aller sur `github.com/VOTRE-USERNAME/pic-dashboard`
3. Cliquer sur `data.csv` → cliquer le crayon ✏️ (Edit) → tout sélectionner → coller le nouveau contenu → **Commit changes**
4. Ou plus simple : cliquer **Add file** → **Upload files** → glisser le nouveau `data.csv` → cocher "replace" → **Commit**
5. Le dashboard se met à jour automatiquement en ~2 minutes

## 📋 Format CSV attendu

Le CSV doit contenir ces colonnes (l'ordre n'est pas important, la détection est automatique) :

| Colonne | Obligatoire | Exemple |
|---------|-------------|---------|
| Organisation | ✅ | Mokap |
| Collègue Référent | | Véronique Perreault |
| Territoire | | Est-de-l'île |
| Statut du projet | | En cours |
| Responsable du dossier IC | | Jacques Drolet |
| Responsable | | Alexandre Caron |
| Étape | ✅ | 1.0. Rencontre & diagnostic initial |
| Statut | | Complété |
| Dernière modification | | 2026-02-09 |
| Commentaires | | Notes diverses |
| Heures internes | | 4 |
| Date de création | | 2025-10-30 |

## 🔒 Import local (prévisualisation)

Le bouton "Importer CSV" sur le dashboard permet de charger un CSV localement pour prévisualisation. Mot de passe : `magellan`. Cette prévisualisation est temporaire et ne modifie pas les données pour les autres utilisateurs.
