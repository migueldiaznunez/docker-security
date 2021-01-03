# Metasploit

## Introducción
Despliegue del servicio metasploit en formato docker con persistencia en base de datos tambien dockerizada

## Pasos

Arranque base de datos
```
$ docker-compose up -d msf-db
```

Arranque servicio metasploit
```
$ docker-compose run --rm msf
```