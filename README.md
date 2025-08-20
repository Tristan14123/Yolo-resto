# 🎰 Yolo RestoO - PWA pour iPhone

Une Progressive Web App (PWA) pour découvrir des restaurants avec une machine à sous magique !

## 📱 Installation sur iPhone

### Méthode 1: Installation automatique
1. Ouvrez Safari sur votre iPhone
2. Allez sur le site web de l'app
3. Un bouton "📱 Installer l'app" apparaîtra en bas à droite
4. Cliquez dessus et suivez les instructions

### Méthode 2: Installation manuelle
1. Ouvrez Safari sur votre iPhone
2. Allez sur le site web de l'app
3. Cliquez sur le bouton "Partager" (carré avec flèche vers le haut)
4. Sélectionnez "Sur l'écran d'accueil"
5. Personnalisez le nom si souhaité
6. Cliquez sur "Ajouter"

## ✨ Fonctionnalités

- 🎰 **Machine à sous interactive** avec animations fluides
- 🍕 **Recherche de restaurants** basée sur votre localisation
- 💰 **Filtres avancés** : budget, régime alimentaire, horaires
- 🎉 **Effets visuels** avec particules et sons
- 📱 **Optimisé iPhone** avec support du notch et safe areas
- 🔄 **Fonctionne hors ligne** grâce au service worker
- 💾 **Sauvegarde automatique** de votre adresse

## 🛠️ Technologies utilisées

- **PWA** (Progressive Web App)
- **Service Worker** pour le cache hors ligne
- **Web App Manifest** pour l'installation
- **CSS Grid/Flexbox** pour le responsive design
- **Web Audio API** pour les effets sonores
- **Geolocation API** pour la localisation
- **OpenStreetMap** pour les données de restaurants

## 📂 Structure du projet

```
yolo-resto-app/
├── index.html          # Application principale
├── manifest.json       # Configuration PWA
├── sw.js              # Service Worker
└── README.md          # Documentation
```

## 🚀 Déploiement

Pour déployer l'app :

1. Hébergez les fichiers sur un serveur HTTPS
2. L'app sera automatiquement installable sur iPhone
3. Les utilisateurs pourront l'ajouter à leur écran d'accueil

## 🎮 Comment utiliser

1. **Entrez votre adresse** dans le champ prévu
2. **Sélectionnez vos préférences** (budget, régime, horaire)
3. **Cliquez sur "Lancer la machine !"**
4. **Découvrez votre restaurant** avec une explosion de particules !

## 🔧 Optimisations iPhone

- Support du **notch** et des **safe areas**
- **Prévention du zoom** sur double-tap
- **Désactivation de la sélection** de texte
- **Optimisation tactile** avec `touch-action`
- **Thème iOS** avec couleurs personnalisées
- **Icône d'app** haute résolution

L'app est maintenant prête à être installée sur votre iPhone ! 🎉
