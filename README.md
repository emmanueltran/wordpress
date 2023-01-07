# wordpress
Déploiment de Wordpress avec Docker

## Descriptif d'utilisation

1. Faites un 'git clone' pour télécharger le projet sur votre machine locale. 
Par exemple:
```console
git clone https://github.com/emmanueltran/wordpress.git <path/folder_name>
```

2. Sur le terminal, vouz aller construire et lancer le projet:
```console
docker-compose up -d
```

Si vous voulez vérifiez que le service MySQL et le service Wordpress sont bien en marche:
Pour le service MySQL:
```console
docker-compose logs db 
```

Pour le service Wordpress:
```console
docker-compose logs db 
```

3. Vous devriez maintenant être en mesure d'accéder à votre application à l'adresse:
```console
http://localhost:8080
```
