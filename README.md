# Example Java Project

## Build Docker Image

```
./gradlew build
docker build --build-arg JAR_FILE=build/libs/\*.jar -t experimentalsoftware/example-java-project:2023-01-30T18.05 .
docker push
```

```
docker run -p 8080:8080 experimentalsoftware/example-java-project:2023-01-30T18.05
```

## References

- https://spring.io/guides/gs/spring-boot-docker/
