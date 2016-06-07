Use docker-compose to fired up the DB

## Setup
```
git clone https://github.com/adentes-org/sofia-db.git && cd sofia-db
```bash
$ docker-compose up -d
```


##Configure Kibana

Se connecter, sélectionner "@timestamp" dans le menu déroulant inférieur de "Settings"
Importer le fichier de configuration (https://raw.githubusercontent.com/adentes-org/docker-sofiane/master/confkibana.json) dans la partie Dashboard
