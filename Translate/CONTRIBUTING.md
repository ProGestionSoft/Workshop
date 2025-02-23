# 📝 Guide de Contribution - Translate i18n

Merci de vouloir contribuer aux traductions des plateformes **Pro Gestion Soft (PGS)** ! 🚀  
Votre aide est précieuse pour rendre PGS accessible à un public international.  

Ce document vous guidera pour proposer des **améliorations de traduction** ou l'ajout d'une **nouvelle langue**.  


## ⚡ Prérequis  

Avant de commencer, assurez-vous d'avoir :  
- Un compte **GitHub**.  
- Une compréhension de base de **Git** et GitHub (fork, commit, pull request).  
- Une bonne maîtrise de la langue que vous souhaitez traduire.  

Si vous êtes nouveau sur GitHub, voici une [introduction à Git](https://git-scm.com/book/fr/v2).  


## 🚀 Comment contribuer ?  

### 📝 1. Vérifier les traductions existantes  
Avant de commencer, consultez les dossiers pour voir si votre langue est déjà disponible :
```bash
Translate-i18n/
├── software/
│  ├── fr/
│  ├── en/
│  └── .../
│
├── landing/
│  ├── fr/
│  ├── en/
│  └── .../
│
├── hiring/
│  ├── fr/
│  ├── en/
│  └── .../
│
├── docs/
│  ├── fr/
│  ├── en/
│  └── .../
│
```

Si votre langue est absente, vous pouvez en proposer une nouvelle !  


### 🔄 2. Améliorer une traduction existante  
Si vous remarquez une **erreur** ou une **formulation maladroite** :  
1. **Forkez** le dépôt en cliquant sur **"Fork"** en haut à droite de la page.  
2. **Clonez** votre fork en local :  
   ```bash
   git clone https://github.com/votre-utilisateur/Translate-i18n.git
   cd Translate-i18n
   ```

3. Modifiez le fichier concerné dans le dossier approprié.
4. Validez vos modifications :
```bash
git add .
git commit -m "Correction de la traduction [nom de la langue]"
git push origin main
```


5. Créez une Pull Request (PR) depuis GitHub.


### 🆕 3. Ajouter une nouvelle langue

Si une langue n'est pas encore disponible, vous pouvez l'ajouter en suivant ces étapes :

1. Créez un dossier avec le code de la langue (ex : es/ pour l'espagnol).
2. Copiez un fichier existant (ex : fr.json ou en.json) pour faciliter la structure.
3. Traduisez le contenu en respectant la mise en forme.
4. Ajoutez votre fichier et soumettez un commit :
```bash
git add .
git commit -m "Ajout de la langue [nom de la langue]"
git push origin main
```
5. Créez une Pull Request pour validation.


## 🏗️ Règles à respecter

- Respectez la structure des fichiers (ne modifiez pas les clés JSON).
- Gardez un langage professionnel et accessible.
- Testez vos traductions pour éviter les erreurs grammaticales.
- Soyez cohérent avec le ton et les termes déjà utilisés.



Merci pour votre contribution ! 🎉

