# Site Vitrine - Société de Construction

Site vitrine moderne et responsive pour une entreprise de construction.

## 🚀 Fonctionnalités

- ✅ Design moderne et professionnel
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Sections : Accueil, Services, Réalisations, À propos, Contact
- ✅ Animations fluides
- ✅ Menu hamburger pour mobile
- ✅ Formulaire de contact
- ✅ Optimisé pour le SEO

## 📦 Déploiement sur Vercel

### Méthode 1 : Déploiement via interface web (Recommandé)

1. **Créer un compte Vercel**
   - Va sur [vercel.com](https://vercel.com)
   - Inscris-toi avec GitHub, GitLab ou email

2. **Préparer le code**
   - Crée un dépôt GitHub avec ces fichiers :
     - index.html
     - styles.css
     - script.js
     - vercel.json

3. **Déployer**
   - Clique sur "New Project" dans Vercel
   - Importe ton dépôt GitHub
   - Vercel détectera automatiquement les fichiers
   - Clique sur "Deploy"
   - Ton site sera en ligne en quelques secondes ! 🎉

### Méthode 2 : Déploiement via CLI

1. **Installer Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Se connecter**
   ```bash
   vercel login
   ```

3. **Déployer**
   ```bash
   vercel
   ```
   - Suis les instructions
   - Appuie sur Entrée pour accepter les valeurs par défaut

4. **Déploiement en production**
   ```bash
   vercel --prod
   ```

## 🎨 Personnalisation

### Modifier les couleurs
Dans `styles.css`, change les variables CSS :
```css
:root {
    --primary-color: #2563eb;  /* Bleu principal */
    --accent-color: #f59e0b;   /* Orange accent */
}
```

### Modifier le contenu
Édite `index.html` pour :
- Changer le nom de l'entreprise (remplace "BâtiPro")
- Modifier les services offerts
- Ajouter/supprimer des sections
- Changer les coordonnées

### Ajouter des images
Pour ajouter de vraies images de projets :
1. Crée un dossier `images/`
2. Ajoute tes images
3. Dans `index.html`, remplace les `background: linear-gradient(...)` par :
```html
<div class="realisation-image" style="background-image: url('images/projet1.jpg');">
```

## 📱 Sections du site

1. **Hero** - Page d'accueil avec call-to-action
2. **Services** - 6 services présentés en grille
3. **Réalisations** - Portfolio de projets
4. **À Propos** - Présentation de l'entreprise
5. **Contact** - Formulaire et coordonnées

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (avec variables CSS)
- JavaScript Vanilla
- Responsive Design
- Animations CSS

## 📝 Notes

- Le formulaire de contact affiche actuellement une alerte. Pour l'intégrer avec un vrai backend, tu peux utiliser :
  - Formspree
  - EmailJS
  - API personnalisée
  - Vercel Serverless Functions

## 🔗 Domaine personnalisé

Après déploiement, tu peux ajouter un domaine personnalisé dans Vercel :
1. Va dans les paramètres du projet
2. Section "Domains"
3. Ajoute ton domaine
4. Suis les instructions DNS

## 📄 Licence

Libre d'utilisation pour ton projet !
