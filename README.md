# GuessTheTrack Flutter App

// ...existing code...

## Déploiement sur GitHub

1. Créez un nouveau dépôt sur GitHub via l'interface web.
2. Dans le terminal, initialisez Git (si ce n'est pas déjà fait) et ajoutez vos fichiers :
   ```
   git init
   git add .
   git commit -m "Initial commit"
   ```
3. Configurez votre dépôt distant :
   ```
   git remote set-url origin https://github.com/Mushhyz/App.git
   ```
4. Poussez votre code sur GitHub :
   ```
   git push -u origin main
   ```

## Déploiement en local

1. Assurez-vous que Flutter est installé sur votre machine et que vous avez configuré un émulateur ou connecté un appareil.
2. Dans le terminal, exécutez :
   ```
   flutter pub get
   flutter run
   ```

## Déploiement continu (optionnel)

- Configurez GitHub Actions pour automatiser tests et déploiement.
- Créez un fichier `.github/workflows/flutter.yml` avec votre configuration de CI/CD.

// ...existing code...
