# Absolut

Absolut est un journal personnel pour retrouver les trades, annoter le ressenti et signaler les erreurs à revoir. Il contient les trois sections **Historique**, **Erreurs à revoir** et **Importer**.

## Utiliser sur ton PC

Décompresse le ZIP dans un dossier, puis ouvre `index.html` dans ton navigateur. Garde ensemble `index.html`, `app.js`, `initial-trades.js` et `styles.css`.

## Mettre sur GitHub

Décompresse le ZIP, puis ajoute les cinq fichiers de ce dossier au dépôt GitHub de ton choix. Pour en faire un site, active **GitHub Pages** dans les réglages du dépôt. Les données saisies sur le site restent dans le navigateur utilisé : elles ne se synchronisent pas automatiquement avec la version ouverte depuis ton PC.

## Données

- Les 16 trades présents dans `EmberSync/ember_history.csv` sont préchargés au premier lancement.
- Le résultat affiché est le profit brut auquel sont ajoutés commission et swap. Le profit brut et les frais restent visibles dans la fiche.
- Les notes et modifications sont enregistrées dans le stockage local du navigateur.
- L'onglet **Importer** accepte les fichiers CSV et HTML/HTM d'historique MT5. Les tickets déjà enregistrés sont ignorés.
- Le fichier source `EmberSync/ember_history.csv` n'est pas modifié.

Pour repartir de zéro dans un navigateur, efface les données de site stockées pour cette adresse. Les trades préchargés réapparaîtront au prochain lancement si le stockage Absolut est absent.
