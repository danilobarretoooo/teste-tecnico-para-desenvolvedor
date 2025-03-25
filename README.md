# 🚀 Teste Técnico – Full Stack (Spring Boot + Angular/React)

## 📌 Descrição do Projeto
Este projeto é um sistema full stack com **autenticação de usuário** e **consumo de API externa**.  
O backend foi desenvolvido com **Spring Boot + Spring Security + JWT**, enquanto o frontend pode ser feito em **React ou Angular**.  

---

## 📑 Requisitos do Projeto

### **1️⃣ Backend (Spring Boot + Spring Security)**
- [x] **Registro de usuário** (`POST /api/auth/register`)  
- [x] **Login** (`POST /api/auth/login`)  
- [x] **Endpoint protegido** (`GET /api/user/profile`)  
- [x] **Consumo de API externa** (`GET /api/external/data`)  

### **2️⃣ Banco de Dados**
- [x] PostgreSQL ou MySQL  
- [x] Persistência com **JPA/Hibernate**  
- [x] Hash de senhas com **BCrypt**  

### **3️⃣ Segurança (Spring Security + JWT)**
- [x] **Autenticação JWT**  
- [x] **Proteção de endpoints**  

### **4️⃣ Consumo de API Externa**
O backend consome uma API pública e expõe os dados via REST. Algumas opções sugeridas:  
🔹 **OpenWeather** – API de previsão do tempo.  
🔹 **ExchangeRates** – API de taxas de câmbio.  
🔹 **OMDb** – API de filmes e séries.  

---

## 💻 Frontend (Angular ou React)
O frontend pode ser feito em **React ou Angular** e deve:  

- [x] Criar **tela de login e registro**  
- [x] Consumir a API do backend para autenticação  
- [x] Criar **tela protegida** exibindo dados do usuário autenticado  
- [x] Exibir os dados consumidos da API externa  

---

## 🛠️ Tecnologias Utilizadas

### **Backend**
✔ Spring Boot  
✔ Spring Security + JWT  
✔ JPA/Hibernate  
✔ Lombok  
✔ Swagger (OpenAPI)  

### **Frontend (escolha um)**
✔ React (com Axios para chamadas HTTP)  
✔ Angular (com HttpClient para chamadas HTTP)  
✔ Bootstrap ou Material UI para estilização  

---

## 🚀 Como Rodar o Projeto

### **📌 Backend**

1️⃣ Clone o repositório:  
```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio/backend


