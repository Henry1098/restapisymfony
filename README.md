# REST API avec Symfony et la plateforme API 


### Installer toutes les dépendances

`make install`

---

### Configurer la Base de données, les variables d'environnement

- Faire une copie du fichier `.env` et le renommer en `.env.local`
- Mettre à jour le fichier avec les informations de la base de données

Si la base de données n'est pas crée, vous pouvez la créer avec doctrine:

```bash
php ./bin/console doctrine:database:create
```

### Lancer le projet

`make dev-server`

(**Note**: Bien penser à utiliser le binaire de Symfony [Symfony binary](https://symfony.com/download) . L'installation du binaire est obligatoire pour tout faire fonctionner)

