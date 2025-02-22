# Levantar el servidor Eureka

```
mvn spring-boot:start
```
# Limpiar y generar el JAR
```bash
mvn clean package
```

# Generar la imagen de Docker 
```bash
docker build -t eureka-server .
```