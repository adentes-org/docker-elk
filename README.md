

## Setup
```
git clone https://github.com/adentes-org/docker-sofiane.git
#Editer logstash/config/logstash.conf si les identifiants admin de couchdb ne sont pas ceux par défaut.
```
```bash
$ docker-compose up -d
```


##Configure Kibana

Se connecter, sélectionner "@timestamp" dans le menu déroulant inférieur de "Settings"
Importer le fichier de configuration (https://raw.githubusercontent.com/adentes-org/docker-sofiane/master/confkibana.json) dans la partie Dashboard
