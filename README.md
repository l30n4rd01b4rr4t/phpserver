# This is a dummy php server

To run this project, you need to run the following command:
```bash
docker-compose up
```

### Access to DB

You need to run the following command to know the DB docker container id:
```bash
docker ps
```

After that, you need to run the following command to access to DB container
```bash
docker exec -it <DOCKER_CONTAINER_ID> bash
```

Now, inside container, you need to run the following command to access to your DB:
```bash
mysql -u dbuser -pdbpass -h localhost test
```

Enjoy it!
