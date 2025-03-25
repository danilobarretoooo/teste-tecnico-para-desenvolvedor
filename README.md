# 🚀 Teste Técnico – Full Stack (Spring Boot + Angular/React)

## 📌 Descrição do Projeto
Este projeto é um sistema full stack com **autenticação de usuário**, **integração com a API do Banco EFI** e **suporte a pagamentos via PIX**.  
O backend foi desenvolvido com **Spring Boot + Spring Security + JWT**, enquanto o frontend pode ser feito em **React ou Angular**.  
A API segue os princípios de uma **RESTful API**, garantindo organização, escalabilidade e boas práticas de desenvolvimento.  

---

## 📑 Requisitos do Projeto

### **1️⃣ Backend (Spring Boot + Spring Security)**
- [x] **Registro de usuário** (`POST /api/auth/register`)  
- [x] **Login** (`POST /api/auth/login`)  
- [x] **Endpoint protegido** (`GET /api/user/profile`)  
- [x] **Consumo da API do Banco EFI** (`GET /api/external/banco-efi`)  
- [x] **Integração com o PIX** (`POST /api/pix/payment`)  

### **2️⃣ Banco de Dados**
- [x] PostgreSQL ou MySQL  
- [x] Persistência com **JPA/Hibernate**  
- [x] Hash de senhas com **BCrypt**  

### **3️⃣ Segurança (Spring Security + JWT)**
- [x] **Autenticação JWT**  
- [x] **Proteção de endpoints**  

### **4️⃣ Consumo de API Externa (Banco EFI + PIX)**
O backend consome a **API do Banco EFI** para realizar operações financeiras e integração com **PIX**.  

🔹 **Banco EFI** – API financeira do banco digital EFI.  
🔹 **PIX** – Integração para geração de pagamentos via PIX.  

---

## 💻 Frontend (Angular ou React)
O frontend pode ser feito em **React ou Angular** e deve:  

- [x] Criar **tela de login e registro**  
- [x] Consumir a API do backend para autenticação  
- [x] Criar **tela protegida** exibindo dados do usuário autenticado  
- [x] Criar **tela de integração com o PIX** (exibir QR Code ou chave PIX gerada)  
- [x] Exibir os dados consumidos da API do Banco EFI  

---

## 🛠️ Tecnologias Utilizadas

### **Backend**
✔ Spring Boot  
✔ Spring Security + JWT  
✔ JPA/Hibernate  
✔ Lombok  
✔ Swagger (OpenAPI)  
✔ Integração com **API do Banco EFI**  
✔ Integração com **PIX**  

### **Frontend (escolha um)**
✔ React (com Axios para chamadas HTTP)  
✔ Angular (com HttpClient para chamadas HTTP)  
✔ Bootstrap ou Material UI para estilização  

---

## 📌 Endpoints da API


```
Autenticação
🔹 Registrar Usuário
POST /api/auth/register
📌 Body (JSON)
{
  "email": "usuario@email.com",
  "password": "senha123"
}

🔹 Login de Usuário
POST /api/auth/login
📌 Body (JSON)
{
  "email": "usuario@email.com",
  "password": "senha123"
}

📌 Resposta (Token JWT)
{
  "token": "eyJhbGciOiJIUzI1..."
}

```


## 📌 Usuário
```
🔹 Buscar Perfil do Usuário (Requer Token JWT)
GET /api/user/profile
Authorization: Bearer <token>
```

## 📌 API Banco EFI

```
🔹 Consultar informações do banco
GET /api/external/banco-efi

📌 Resposta (Exemplo)
{
  "banco": "EFI",
  "servicos": ["PIX", "Transferências", "Pagamentos"]
}

Integração PIX
🔹 Gerar pagamento PIX
POST /api/pix/payment
Authorization: Bearer <token>

📌 Body (JSON)
{
  "valor": 100.00,
  "chave_pix": "email@dominio.com",
  "descricao": "Pagamento de serviço"
}
📌 Resposta (Exemplo - QR Code)
{
  "qr_code": "00020126330014BR.GOV.BCB.PIX...",
  "qrcode_base64": "/9j/4AAQSkZJRgABAQAAAQAB..."
}
```
### **✅Critérios de Avaliação**
✔ Código limpo e organizado

✔ API RESTful bem estruturada

✔ Segurança na autenticação (hash de senha + JWT)

✔ Integração correta com a API do Banco EFI

✔ Integração funcional com PIX

✔ Frontend responsivo e funcional

✔ Uso correto de consumo de APIs no frontend e backend







### **📝 Autor**
👤 Danilo Barreto Lima Santos
