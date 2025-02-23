# 📖 Translate - i18n

Bienvenue dans le dépôt **Translate - i18n** du projet **Pro Gestion Soft (PGS)** ! 🎉  

Ce dépôt a pour but de centraliser les traductions des différentes plateformes PGS afin de rendre l'écosystème accessible à un maximum d'utilisateurs à travers le monde.  

## 🌍 Objectif du projet  

Les contributions ici concernent la traduction et l'amélioration des contenus linguistiques des plateformes PGS, notamment :  

- 🖥️ **Le logiciel PRO GESTION SOFT**  
- 📄 **La documentation PGS**  
- 🌐 **Le site officiel**  
- 🏢 **Le site de recrutement**  
- 🛒 **Le marketplace et les templates**  

Vous pouvez :  
- Proposer une **nouvelle langue** non encore disponible.  
- **Améliorer** une traduction existante en français ou en anglais.  
- Corriger des erreurs de traduction, améliorer la fluidité et la cohérence.  


## 🏗️ Structure du projet  

Les fichiers de traduction sont organisés dans des dossiers correspondant aux différentes plateformes :

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

Chaque dossier contient des fichiers au format `.json` ou `.md` selon la plateforme.  


## 🚀 Comment contribuer ?  

- 📝 **1. Vérifier si votre langue est disponible** :  
  Consultez les dossiers pour voir si votre langue existe déjà. Si elle est absente, vous pouvez en proposer une nouvelle !  
- 🔄 **2. Améliorer une traduction existante** :  
  Si vous trouvez des erreurs ou des formulations maladroites, vous pouvez les corriger en proposant un **Pull Request**.  
- 🆕 **3. Ajouter une nouvelle langue** :   
  - Créez un dossier au format ISO de la langue (ex: `es/` pour l'espagnol).  
  - Copiez un fichier existant (`fr.json` ou `en.json`) et traduisez-le. Les fichiers de traduction sont au format JSON.
  Exemple :

  ```bash
  json
  {
    "welcome_message": "Bienvenue sur PRO GESTION SOFT !",
    "login_button": "Se connecter"
  }
  ```
  - Soumettez une **Pull Request** une fois vos modifications terminées :

  ```bash
  git add .
  git commit -m "Ajout d'une traduction pour [langue] sur [plateforme]"
  git push origin <votre-branche>
  ```


Merci pour votre contribution ! 🎉🚀