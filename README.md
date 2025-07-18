
# MedSecure - Plateforme Médicale Sécurisée

## Description du projet

MedSecure est une plateforme médicale sécurisée conçue pour la gestion des dossiers patients, des rendez-vous et des communications médicales au Cameroun. Elle facilite la coordination entre patients, médecins, infirmières et administrateurs hospitaliers.

## Fonctionnalités principales

### Pour les Patients
- Gestion des rendez-vous médicaux
- Consultation du dossier médical
- Messagerie sécurisée avec les professionnels de santé
- Suivi des ordonnances et prescriptions

### Pour les Médecins
- Gestion des patients assignés
- Création d'ordonnances et prescriptions
- Consultation des dossiers médicaux
- Planification des consultations

### Pour les Infirmières
- Enregistrement des patients
- Saisie des paramètres vitaux
- Attribution des patients aux médecins
- Gestion des admissions

### Pour les Administrateurs
- Gestion des utilisateurs
- Supervision des activités
- Génération de rapports
- Configuration du système

## Technologies utilisées

- **Frontend**: React 18 avec TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Shadcn/UI
- **State Management**: React Context API
- **Routing**: React Router DOM
- **Build Tool**: Vite
- **Data Fetching**: TanStack Query

## Installation et démarrage

### Prérequis
- Node.js (version 18 ou supérieure)
- npm ou yarn

### Installation
```bash
# Cloner le projet
git clone <YOUR_GIT_URL>

# Naviguer dans le répertoire
cd medsecure

# Installer les dépendances
npm install

# Démarrer le serveur de développement
npm run dev
```

Le projet sera accessible à l'adresse `http://localhost:8080`

## Déploiement

### Déploiement sur Vercel
1. Connectez votre repository GitHub à Vercel
2. Vercel détectera automatiquement la configuration grâce au fichier `vercel.json`
3. Le déploiement se fera automatiquement à chaque push sur la branche principale

### Build de production
```bash
npm run build
```

Les fichiers de production seront générés dans le dossier `dist/`.

## Structure du projet

```
src/
├── components/         # Composants réutilisables
│   ├── auth/          # Composants d'authentification
│   ├── dashboard/     # Tableaux de bord par rôle
│   ├── ui/            # Composants UI de base
│   └── ...
├── contexts/          # Contextes React
├── hooks/             # Hooks personnalisés
├── pages/             # Pages principales
└── lib/               # Utilitaires et helpers
```

## Contribution

1. Fork le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Committez vos changements (`git commit -am 'Ajouter nouvelle fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Créez une Pull Request

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## Contact

Pour toute question ou suggestion, contactez l'équipe MedSecure Cameroun.
