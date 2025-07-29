# Instructions pour créer un repository GitHub - SinerjiOps

## Étape 1 : Créer un compte GitHub
1. Allez sur [github.com](https://github.com)
2. Cliquez sur "Sign up" (S'inscrire)
3. Remplissez le formulaire avec votre email, mot de passe, et nom d'utilisateur
4. Vérifiez votre email

## Étape 2 : Créer un nouveau repository
1. Connectez-vous à GitHub
2. Cliquez sur le bouton "+" en haut à droite
3. Sélectionnez "New repository"
4. Remplissez les informations :
   - **Repository name :** `sinerjiops-maintenance`
   - **Description :** `Système de gestion de maintenance SinerjiOps`
   - **Public** (ou Private si vous préférez)
   - **Ne pas cocher** "Add a README file" (nous en avons déjà un)
5. Cliquez sur "Create repository"

## Étape 3 : Installer Git (si pas déjà fait)
1. Téléchargez Git depuis [git-scm.com](https://git-scm.com)
2. Installez Git en suivant les instructions
3. Ouvrez PowerShell ou Command Prompt

## Étape 4 : Configurer Git
```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```

## Étape 5 : Initialiser le repository local
1. Ouvrez PowerShell
2. Naviguez vers votre dossier :
```bash
cd "C:\Users\aminc\Apprentissage-Coding"
```

3. Initialisez Git :
```bash
git init
```

4. Ajoutez tous les fichiers :
```bash
git add .
```

5. Faites le premier commit :
```bash
git commit -m "Initial commit - SinerjiOps Maintenance System"
```

## Étape 6 : Connecter au repository GitHub
1. Copiez l'URL de votre repository GitHub (format : `https://github.com/votre-username/sinerjiops-maintenance.git`)

2. Ajoutez le remote :
```bash
git remote add origin https://github.com/votre-username/sinerjiops-maintenance.git
```

3. Poussez le code :
```bash
git branch -M main
git push -u origin main
```

## Étape 7 : Vérification
1. Allez sur votre repository GitHub
2. Vous devriez voir tous vos fichiers :
   - `clean-version.html` (version avec interface de création de compte)
   - `logo.png`
   - `README.md`
   - etc.

## Fichiers importants à inclure :
- ✅ `clean-version.html` (version principale avec SinerjiOps)
- ✅ `logo.png` (logo de l'entreprise)
- ✅ `README.md` (documentation)
- ✅ `index.html` (version alternative)
- ✅ `index-backup.html` (sauvegarde)

## Prochaines étapes :
1. Partagez l'URL de votre repository
2. Configurez GitHub Pages pour héberger le site
3. Ajoutez des collaborateurs si nécessaire

## Support :
Si vous rencontrez des problèmes, consultez la documentation GitHub ou demandez de l'aide ! 