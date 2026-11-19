# Guinée — DRM / PReM MPA (P513145)

Tableau de bord du Pacte de mise en œuvre de 100 jours. Copie autonome du modèle réutilisable; **ne pas modifier le dépôt SIRA Guinée**.

## Source et état initial

- Classeur source : `PACT_100_JOURS_MASTER.xlsx`, copie inchangée du fichier transmis par l’équipe.
- 77 activités dans `Suivi simplifié`, avec cinq groupes fixes, et huit marchés dans `Marchés prioritaires`.
- Date de début : 12 octobre 2026; durée : 100 jours.
- Les statuts et avancements sont ceux du classeur; les données « À confirmer » ne sont pas certifiées. Les montants manquants ne sont pas estimés.

## Publication GitHub Pages

1. Créer un dépôt **distinct**, par exemple `guinee-drm-100-jours`, sur GitHub.
2. Décompresser ce paquet et déposer **tout son contenu** à la racine du dépôt, y compris `.github/workflows/update-dashboard.yml`.
3. Dans **Settings → Pages**, choisir **Deploy from a branch**, branche `main`, dossier `/(root)`.
4. Dans **Actions**, vérifier que les workflows sont autorisés et que les permissions du workflow permettent **Read and write permissions** (si nécessaire).
5. Déclencher `Update project dashboard from Excel` via **Actions → Run workflow**.
6. Vérifier les 77 activités, les cinq groupes, les huit marchés, les dates et la navigation sur la page publiée.

## Mise à jour

1. Modifier uniquement les informations réelles dans les onglets du classeur, en préservant les dix colonnes et les cinq groupes.
2. Remplacer `PACT_100_JOURS_MASTER.xlsx` dans le dépôt et valider le commit.
3. Le workflow régénère `data.js` et publie la nouvelle version via GitHub Pages.

**Attention :** le suivi calendaire est calculé dynamiquement à partir du début du pacte et des jours relatifs. Aucun statut, montant ou progrès n'a été inventé.
