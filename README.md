# 🚀 Cadastro de Usuários - Spring Boot

API REST para gerenciamento de usuários com **Spring Boot** e **PostgreSQL**.  
Permite **cadastrar, buscar, atualizar e excluir** usuários de forma simples.

### 🔧 Tecnologias
- Java 17+
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Lombok

### 📡 Endpoints
- `POST /usuario` → criar usuário  
- `GET /usuario?email=xxx` → buscar por email  
- `PUT /usuario?id=1` → atualizar por ID  
- `DELETE /usuario?email=xxx` → excluir por email  

### ▶️ Como rodar
1. Configure o PostgreSQL no `application.properties`  
2. Execute o projeto:  
   ```bash
   ./mvnw spring-boot:run
Acesse em: http://localhost:8080/usuario

💼 Projeto desenvolvido para estudo e demonstração de habilidades com Spring Boot.
