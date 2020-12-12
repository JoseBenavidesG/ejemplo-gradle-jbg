# Getting Started

## Windows

### Compile Code
* ./gradlew clean compile -e

### Test Code
* ./gradlew clean test -e

### Jar Code
* ./gradlew clean package -e

### Run Jar
* Local:      ./gradlew spring-boot:run 
* Background: nohup bash gradlew spring-boot:run &

### Testing Application
* Abrir navegador: http://localhost:8081/rest/mscovid/test?msg=testing
