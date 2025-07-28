# Configuration des variables d'environnement

## Variables disponibles

### ALLOWED_HOSTS
Liste des hôtes autorisés pour Vite, séparés par des virgules.

**Exemple :**
```bash
ALLOWED_HOSTS=app-c2ad4f96-00a7-4290-be59-af1e7f0d8f6f.cleverapps.io,autre-hote.com
```

## Configuration

1. Créez un fichier `.env` à la racine du projet
2. Ajoutez vos variables d'environnement :

```bash
# .env
ALLOWED_HOSTS=app-c2ad4f96-00a7-4290-be59-af1e7f0d8f6f.cleverapps.io
```

## Déploiement

Pour Clever Cloud, configurez la variable d'environnement dans votre dashboard ou via l'API :

```bash
clever env set ALLOWED_HOSTS "app-c2ad4f96-00a7-4290-be59-af1e7f0d8f6f.cleverapps.io"
``` 