oidc provider: https://hub.docker.com/r/qlik/simple-oidc-provider

to run the project:
```
docker-compose -f quickstart.yml -f quickstart-postgres.yml -f quickstart-oathkeeper.yml up --build --force-recreate
```
---

## notes:


docker-compose -f quickstart.yml -f quickstart-postgres.yml -f quickstart-oathkeeper.yml down -v

docker-compose -f quickstart.yml -f quickstart-postgres.yml -f quickstart-oathkeeper.yml rm -fsv


http://127.0.0.1:4455



mailslurper: http://127.0.0.1:4436


