# Sistema de Gestão de Usuários - API REST

API RESTful desenvolvida para o gerenciamento completo de usuários, focada em uma arquitetura limpa, separação de responsabilidades e persistência de dados eficiente.

## Tecnologias Utilizadas
- **Linguagem:** Java 17
- **Framework:** Spring Boot 3+
- **Persistência:** Spring Data JPA / Hibernate
- **Banco de Dados:** PostgreSQL
- **Gerenciamento de Dependências:** Maven
- **Ferramentas de Teste:** Postman

## Arquitetura e Funcionalidades
O projeto foi estruturado seguindo o padrão **MVC** (Model-View-Controller) e dividido em 3 camadas principais:
1. **Controller:** Exposição dos endpoints e manipulação de requisições/respostas HTTP.
2. **Service:** Camada de lógica de negócio e regras de validação.
3. **Repository:** Interface de comunicação com o banco de dados via JPA.

**Principais Recursos:**
- CRUD completo com 4 endpoints (POST, GET, PUT, DELETE).
- Mapeamento de entidades utilizando **Lombok** e **Builder Pattern** para código mais limpo.
- Validação de payloads JSON e códigos de status HTTP apropriados.

## Como Executar
1. Clone o repositório.
2. Configure o `application.properties` com suas credenciais do PostgreSQL.
3. Execute o comando `mvn spring-boot:run`.
4. A API estará disponível em `http://localhost:8080`.
