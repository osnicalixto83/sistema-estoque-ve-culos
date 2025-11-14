# Sistema Automotivo – Gestão de Estoque de Veículos

## Descrição
CRUD para gestão de veículos (Java + Spring Boot + MySQL).

## Como rodar (Backend)
1. Configurar banco MySQL (ver `database/schema.sql`)
2. Ajustar `application.properties` com credenciais do DB
3. Build e run:
   ```bash
   ./mvnw clean package
   java -jar target/app.jar
