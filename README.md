# simple-msf4j-app

Exemplo simples de MSF4J app com maven (e Docker)

## Criação

O projeto foi criado com o arquétipo da WSO2:

```sh
mvn archetype:generate -DarchetypeGroupId=org.wso2.msf4j \
-DarchetypeArtifactId=msf4j-microservice -DarchetypeVersion=2.5.2 \
-DgroupId=br.com.vertigo.exemplo -DartifactId=simple-msf4j-app -Dversion=0.1-SNAPSHOT \
-Dpackage=br.com.vertigo.service -DserviceClass=HelloService
```

