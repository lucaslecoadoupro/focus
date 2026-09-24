# Focus

Appli d'analyse d'images pour les élèves.
© Lucas Le Coadou - Professeur d'espagnol dans l'académie de Montpellier

## Mise en ligne (une seule fois)

1. Crée un dépôt **public** sur GitHub, par exemple `focus`.
2. Dépose dedans tout le contenu de ce dossier : `index.html`, `data.json`, le dossier `images/` et le fichier `.nojekyll`.
3. Dans le dépôt, va dans **Settings > Pages**. Choisis **Deploy from a branch**, la branche `main` et le dossier `/ (root)`, puis enregistre.
4. Au bout d'une minute environ, le site est en ligne à l'adresse `https://<ton-pseudo>.github.io/focus/`.

## Créer ta clé d'accès enseignant (une seule fois)

1. Sur GitHub, va dans **Settings > Developer settings > Personal access tokens > Fine-grained tokens**, puis clique sur **Generate new token**.
2. Dans **Repository access**, choisis **Only select repositories**, puis le dépôt `focus`.
3. Dans **Permissions > Repository permissions**, règle **Contents** sur **Read and write**.
4. Choisis une date d'expiration (par exemple la fin de l'année scolaire), puis génère la clé.
5. Copie la clé et range-la dans ton gestionnaire de mots de passe. GitHub ne te la remontrera plus.

Cette clé ne donne accès qu'à ce dépôt.

## Au quotidien

1. Ouvre le site et clique sur **Espace enseignant** en bas de la page.
2. Colle ta clé. Coche « Rester connecté » seulement sur ton ordinateur personnel.
3. Ajoute ou modifie tes analyses. Chaque enregistrement est envoyé directement dans le dépôt.
4. Les élèves voient les changements une à deux minutes plus tard.

Sur un ordinateur partagé, clique sur **Se déconnecter** en bas de la page quand tu as fini.

## En cas de problème

Si ta clé est perdue ou a fuité, supprime-la sur GitHub (dans la même page que pour la créer) et crée-en une nouvelle. L'ancienne cesse immédiatement de fonctionner.
