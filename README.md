# Project Name
Project TL;DR. This should provide a 2-5 sentence description of the project and what it's used for. It should make sense to a 5 year old*.
asdf
\* provided the 5 year old has decent understanding of web services.

### Team Owner
Which team owns it, possibly with a link to confluence if you're feeling saucy.

## How to start working on the project

### Dependencies
List of things and versions you'll need to install
ie:
- mysql > 5.6
- Java 7
- maven

### Any other unscriptable setup steps
- Configure Nginx in some wacky way
- Proxy your maven repo to nexus
- Set up a certain mysql account or schema

### Compile / Build / Test
The commands and flags to build the project.
ie:
```sh
    # compile
    mvn clean install
    # test
    mvn verify -Pintegration-test
```

### Any other configuration steps
```sh
	cp config/sample-config.yml config/myconfig.yml
```

### How to run locally
All the steps to get the service running locally and verify that it is up and running correctly.
ie:
```sh
java -jar target/service-name-1.0.0-SNAPSHOT.jar --spring.config.location=config/myconfig.yml
curl http://localhost:9000/sm-sessions/healthcheck
```
