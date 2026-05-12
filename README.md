# QHSE Control - Page de candidature accompagnement

Application statique légère pour la page de candidature QHSE Control, prête à être déployée sur Railway.

## Installation locale

```bash
npm install
npm start
```

URL locale :

- http://localhost:3000

## Déploiement Railway

1. Connecter le dépôt GitHub à Railway.
2. Railway exécute automatiquement :
   - `npm install`
   - `npm start`

L'application écoute le port fourni par Railway via `process.env.PORT`.

## Formulaire

Les candidatures sont envoyées via Formspree avec l'endpoint :

- `https://formspree.io/f/mwvyyrze`
