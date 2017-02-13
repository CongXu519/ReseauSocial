# Réseau Social
Ce projet de j2ee est basé sur Spring Boot et thymeleaf.

# Marche à suivre

Lancement des différents service (chaque service se lance d'en un terminal distinct) :

### Authentification

```
cd authentification
mvn spring-boot:run
```

### Document

```
cd document-service
mvn spring-boot:run
```

### Message

```
cd message-service
mvn spring-boot:run
```

### UserProfil

```
cd userprofil-service
mvn spring-boot:run
```

## Lancement de l'application

A la racine du projet, une fois tous les services démarrés :

```
mvn spring-boot:run
```

## Utilisation de l'application

Le projet lancé, il faut maintenant aller à l'adresse (dans votre navigateur internet):

```
localhost:8080/userlogin
```

Vous arriverez sur la page d'authentification.

