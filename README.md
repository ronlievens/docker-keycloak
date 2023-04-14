Dit project is een docker compose bestand die een keycloak service start.
[Voor meer informatie lees hier](https://www.keycloak.org/getting-started/getting-started-docker).

# Dashboards

- [Keycloak Admin Console.](http://127.0.0.1:18080/)

## Opstarten en afsluiten

Om te starten voer het command uit (`-d` zorgt dat Jenkins en SonarQube als een achtergrond services gestart worden):

```shell
docker-compose up -d start-dev
```

Om af te sluiten voer het commando uit:

```shell
docker-compose down
```
