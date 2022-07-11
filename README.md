# Basic-postgresql-docker
## Connect with db:
1. get the docker-compose.yml
2. run  `docker-compose -f docker-compose.yml up`
3. Open a new terminal and find `CONTAINER-ID` by `docker ps` command
4. Then run `docker exec -it container_id sh`
5. Next run `su - postgres`
6. To finish run  `psql` and you are in!

### Pgadmin
In browser: `http://localhost:5050/`
login: admin@admin.com
pass: root
