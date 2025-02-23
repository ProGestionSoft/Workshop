# Guide de contribution  

Merci de votre intérêt pour **Workshop** ! Votre aide est précieuse pour améliorer et enrichir les différents projets de cet espace collaboratif. Ce document vous guidera à travers le processus de contribution.  


## 🚀 Comment contribuer ?  

### 1. **Fork & clone le dépôt**  
Commencez par forker le dépôt et cloner votre propre copie :  

```bash
git clone https://github.com/votre-utilisateur/Workshop.git
cd Workshop
```

Ajoutez ensuite le dépôt original comme **remote upstream** pour rester à jour avec les dernières modifications :  

```bash
git remote add upstream https://github.com/ProGestionSoft/Workshop.git
git fetch upstream
```

### 2️. **Créer une branche**  
Travaillez sur une nouvelle branche correspondant à votre contribution :  

```bash
git checkout -b feature/nom-fonctionnalité
```

Pour une correction de bug, utilisez :  

```bash
git checkout -b fix/nom-du-bug
```

### 3. **Développement & tests**  
- Faites vos modifications en respectant les bonnes pratiques de code.  
- Testez votre code pour éviter les régressions.  
- Vérifiez que votre contribution respecte la structure et la logique du projet.  

---

### 4️⃣ **Commit & push**  
Une fois satisfait(e) de vos modifications :  

1. **Ajoutez vos changements** :  
   ```bash
   git add .
   ```
2. **Rédigez un message de commit clair** :  
   ```bash
   git commit -m "Ajout : nouvelle fonctionnalité X"
   ```
3. **Poussez votre branche sur votre fork** :  
   ```bash
   git push origin feature/nom-fonctionnalité
   ```


### 5️⃣ **Créer une pull request**  
Rendez-vous sur GitHub et ouvrez une **Pull Request** en respectant les points suivants :  

- Décrivez votre contribution de manière claire.  
- Assurez-vous que votre PR est assignée à un relecteur.  
- Liez votre pull request à une issue si elle est liée à un problème existant.  


Merci pour votre implication et vos contributions !