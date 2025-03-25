🚀 Teste Técnico – Full Stack (Spring Boot + Angular/React)
📌 Descrição do Projeto
Este projeto é um sistema full stack com autenticação de usuário e consumo de API externa. O backend foi desenvolvido com Spring Boot + Spring Security + JWT, enquanto o frontend pode ser feito em React ou Angular.

📑 Requisitos do Projeto
1️⃣ Backend (Spring Boot + Spring Security)
 Registro de usuário (POST /api/auth/register)

 Login (POST /api/auth/login)

 Endpoint protegido (GET /api/user/profile)

 Consumo de API externa (GET /api/external/data)

2️⃣ Banco de Dados
 PostgreSQL ou MySQL

 Persistência com JPA/Hibernate

 Hash de senhas com BCrypt

3️⃣ Segurança (Spring Security + JWT)
 Autenticação JWT

 Proteção de endpoints

4️⃣ Consumo de API Externa
O backend consome uma API pública e expõe os dados via REST. Algumas opções sugeridas:
🔹 OpenWeather – API de previsão do tempo.
🔹 ExchangeRates – API de taxas de câmbio.
🔹 OMDb – API de filmes e séries.

💻 Frontend (Angular ou React)
O frontend pode ser feito em React ou Angular e deve:

 Criar tela de login e registro

 Consumir a API do backend para autenticação

 Criar tela protegida exibindo dados do usuário autenticado

 Exibir os dados consumidos da API externa

🛠️ Tecnologias Utilizadas
Backend
✔ Spring Boot
✔ Spring Security + JWT
✔ JPA/Hibernate
✔ Lombok
✔ Swagger (OpenAPI)

Frontend (escolha um)
✔ React (com Axios para chamadas HTTP)
✔ Angular (com HttpClient para chamadas HTTP)
✔ Bootstrap ou Material UI para estilização

