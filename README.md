# Whatsapp clone (fullstack project) Spring boot 3, Angular 18, Bootstrap, PostgreSQL, Keycloak
Spring boot backend of the whatsapp clone

### Key Features:
- 💬 Real-time messaging
- 👥 Conversations management
- 📁 File sharing (images, videos, documents)
- 🔐 Authentication and Authorization (Role management) with Keycloak (OAuth2)
- 🏢 Hexagonal architecture


## Usage
### Prerequisites
- [JDK 21](https://adoptium.net/temurin/releases/)
- [PostgreSQL](https://www.postgresql.org/download/)
- IDE ([VSCode](https://code.visualstudio.com/download), [IntelliJ](https://www.jetbrains.com/idea/download/))
- Docker ([Docker Desktop](https://docs.docker.com/engine/install/))

### Clone the repository
``git clone https://github.com/rafi99-bat/whatsapp-clone-backend.git``

### Launch

#### Run keycloak
``docker-compose src/main/docker/keycloak.yml up -d``

#### Maven
``./mvnw spring-boot:run``