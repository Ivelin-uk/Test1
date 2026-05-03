# Hello Spring

Spring Boot MVC проект с контролер, който връща `view` (`Thymeleaf`).

## Локално стартиране

```bash
mvn spring-boot:run
```

След стартиране отвори:

`http://localhost:8080`

## Railway

Проектът е подготвен за Railway с:

- `spring-boot-starter-web` и `spring-boot-starter-thymeleaf`
- MVC контролер на `/`
- `server.port=${PORT:8080}` в `application.properties`
