# 🛠️ Guide de Contribution - AppBot  

Bienvenue et merci de votre intérêt pour l’amélioration d’**AppBot** ! 🚀  
Ce guide vous aidera à contribuer efficacement au projet.  


## 🏗️ Comment contribuer ?  

### 1️⃣ **Signaler un bug ou une amélioration**  
Avant toute contribution, vérifiez si une **Issue** existe déjà.  
- 📌 **Signaler un bug** : [Ouvrir une issue](https://github.com/ProGestionSoft/AppBot/issues)  
- 💡 **Proposer une amélioration** : [Suggérer une fonctionnalité](https://github.com/ProGestionSoft/AppBot/issues)  

### 2️⃣ **Proposer une Pull Request (PR)**  
Si vous souhaitez apporter des modifications au code :  

#### 🛠️ 1. Forker et cloner le dépôt  
```bash
git clone https://github.com/ProGestionSoft/AppBot.git
cd AppBot
```

### 🔧 2. Créer une branche dédiée

`git checkout -b feature/nom-de-la-fonctionnalite`

### 💻 3. Faire vos modifications

Assurez-vous de :
- Respecter la structure du projet.
- Écrire un code propre et bien commenté.
- Tester votre code avant soumission.

### ✅ 4. Commiter vos changements
```bash
git add .
git commit -m "Ajout : nouvelle fonctionnalité X"
git push origin feature/nom-de-la-fonctionnalite
```

### 🔄 5. Créer une Pull Request

Rendez-vous sur GitHub et ouvrez une Pull Request en expliquant :
- Les changements effectués.
- Leur impact sur le projet.
- Les tests réalisés.


## 📂 Structure du projet

📦 AppBot
 ┣ 📂 src
 ┃ ┣ 📜 index.js  # Fichier principal
 ┃ ┣ 📜 bot.js    # Gestion des commandes Telegram
 ┃ ┣ 📜 api.js    # Intégration avec les API PGS
 ┃ ┗ 📜 config.js # Configuration du bot
 ┣ 📜 .env.example # Exemple de fichier de configuration
 ┣ 📜 package.json # Dépendances du projet
 ┗ 📜 README.md    # Documentation principale
