# GuessTheTrack Flutter App

// ...existing code...

## Déploiement sur GitHub

1. Créez un nouveau dépôt sur GitHub via l'interface web.
2. Dans le terminal de votre projet, initialisez Git (si ce n'est pas déjà fait):
   ```
   git init
   ```
3. Ajoutez tous les fichiers et faites un commit en exécutant séparément:
   ```
   git add .
   git commit -m "Initial commit"
   ```
   ou en une seule ligne:
   ```
   git add . && git commit -m "Initial commit"
   ```
4. Ajoutez le dépôt distant:
   ```
   git remote add origin https://github.com/votre-nom-utilisateur/nom-du-depot.git
   ```
5. Poussez votre code:
   ```
   git push -u origin master
   ```

## Déploiement continu (optionnel)

- Configurez GitHub Actions pour automatiser tests et déploiement.
- Créez un fichier `.github/workflows/flutter.yml` avec votre configuration de CI/CD.

// ...existing code...
