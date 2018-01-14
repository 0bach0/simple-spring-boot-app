# Simple Spring Boot Application 

Follow this tutorial: https://spr.com/part-1-getting-started-again-build-a-web-app-with-spring-boot/

This application runs on port 8080 and have only 1 endpoint at /

You can check it by open terminal:

```bash
$ curl localhost:8080
Greetings from Spring Boot!
```

# Build & running

You can run it directly by running

```bash
java -jar gs-spring-boot-0.1.0.jar
```

Or modify and rebuild it with

```bash
./gradlew clean build
```

The jar file will be placed in /build/libs