### 🤷🏼‍♂️ PREREQUISITE DEV

- Java version 11 (at least)
- Maven
- Docker environment
- Docker compose

### 🐳 RUNNING THE APP DOCKER

```shell
mvn clean install -Dmaven.test.skip # install all deps for backend from parent pom file
docker-compose --build -d --force-recreate # deploy service to docker
```

### 🚚 SERVICES
- elasticsearch port 9200
- zookeeper port 2181
- kafka port 9092

