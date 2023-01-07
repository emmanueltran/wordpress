# wordpress
Déploiment de Wordpress avec Docker

## Descriptif d'utilisation

Acant de commencer, assurez vous que vous avez toutes les installation de Docker nécessaire: [Docker](https://docs.docker.com/get-docker/).
Vous devez aussi avoir un compte Docker Hub.

1. Faites un 'git clone' pour télécharger le projet sur votre machine locale. 
Par exemple:
```console
git clone https://github.com/emmanueltran/wordpress.git <path/folder_name>
```

2. Récupérer les images sur Docker Hub:

Sur le terminal:
Pour l'image MySQL:
```console
docker pull tranemmanuel/wordpress:db
```

Pour l'image Wordpress:
```console
docker pull tranemmanuel/wordpress:wp
```

3. Assurez vous que vous etes bien dans le bon répertoire (path/wordpress).
Vous allez lancez les conteneurs:
```console
docker-compose up
```

Si vous voulez vérifiez que le service MySQL et le service Wordpress sont bien en marche:

Pour le service MySQL:
```console
docker-compose logs db 
```

Pour le service Wordpress:
```console
docker-compose logs wordpress 
```

4. Vous devriez maintenant être en mesure d'accéder à votre application à l'adresse:
```console
http://localhost:8000
```
