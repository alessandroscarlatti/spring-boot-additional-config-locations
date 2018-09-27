### Specify a different external config location.

```
gradlew build
cd build
java -jar demo-0.0.1-SNAPSHOT.jar --spring.config.location=classpath:/,file:../../config/
```