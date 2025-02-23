# 🤖 AppBot - Le bot Telegram de PGS  

**AppBot** est un bot Telegram permettant d'interagir avec les API de **Pro Gestion Soft (PGS)** directement depuis Telegram. Il offre un accès rapide aux fonctionnalités essentielles sans quitter l’application.  

🚀 **Principales fonctionnalités** :  
-  Affichage des derniers articles du blog PGS.  
- Envoi de messages au support client.  
- Exécution de requêtes API spécifiques.  
- Gestion des erreurs et réponses asynchrones.  

## 🔧 Installation et Configuration  

### 🛠️ 1. Prérequis  
Avant d'installer **AppBot**, assurez-vous d’avoir :  
- **Node.js** (version 16+ recommandée).  
- Un **token d'API Telegram** obtenu via **@BotFather**.  
- Un accès aux API **Pro Gestion Soft (PGS)**. 

### 📥 2. Cloner le projet  
```bash
git clone https://github.com/ProGestionSoft/AppBot.git
cd AppBot
```

### ⚙️ 3. Installer les dépendances

`npm install`

### 🔑 4. Configurer les variables d’environnement

Créez un fichier .env et ajoutez vos informations :

```bash
BOT_TOKEN=VOTRE TOKEN TELEGRAM
PGS_SECRET_TOKEN=VOTRE TOKEN PGS
PGS_API_URL=L'URL de PGS API
```

### ▶️ 5. Lancer le bot

`npm start`

Le bot est maintenant opérationnel ! 🚀