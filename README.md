# Maven-app

Commands
```maven-app> mvn clean```
```maven-app> mvn package```
```maven-app> mvn compile```
```maven-app/main-app> mvn exec:java```

mvn compile won't work unless mvn package has been executed before

Create a new project:
```mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false```
