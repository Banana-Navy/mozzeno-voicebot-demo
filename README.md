# Assistant vocal mozzeno — démonstration

Cette branche publique contient uniquement les fichiers statiques nécessaires à la
landing de démonstration de l'assistant vocal mozzeno.

## Périmètre

- Démonstration sans engagement, sans décision de crédit et sans accès à un dossier.
- Ne saisissez aucune donnée personnelle, bancaire ou sensible pendant le test.
- Les capacités qui dépendent des outils métier restent simulées jusqu'à leur
  déploiement sécurisé.
- Le microphone n'est demandé qu'après une action explicite de l'utilisateur.

## Connexion vocale

Une version vocale publiée sur GitHub Pages utilise uniquement l'identifiant public
d'un agent de démonstration. Son origine doit aussi être limitée côté fournisseur avant
publication. Aucune clé API, URL signée, jeton de session ou configuration privée n'est
publiée dans ce dépôt.

Si la configuration n'est pas disponible, l'interface l'indique sans lancer de voix
de secours ni simuler une connexion réussie.

## Provenance de l'artefact

L'artefact est construit depuis une liste d'autorisation stricte. Il exclut notamment
les prompts, bases documentaires, scripts d'orchestration, migrations, fichiers PDF,
fixtures, journaux et secrets. `MANIFEST.sha256` permet de vérifier l'intégrité des
fichiers livrés.

Conception et intégration : Banana Navy. Les marques et visuels mozzeno demeurent la
propriété de leurs titulaires respectifs.
