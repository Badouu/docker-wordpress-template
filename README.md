# DOCKER WORDPRESS TEMPLATE

## Installation & utilisation

Utilisez la commande suivante pour installer les prerequis et lancer les containers :

```sh
$ docker-compose up -d
```

Utilisez la commande suivante pour supprimer les containers et les donnees persistantes :
```sh
$ docker-compose down --volumes
```

Utilisez la commande suivante pour configurer le container wordpress :
```sh
$ docker exec -it wordpress_wordpress_1 bash
```

## Technologies

| Technology | Website |
| ------ | ------ |
| Docker | https://hub.docker.com/ |