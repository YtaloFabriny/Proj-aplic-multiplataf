# 🔌 API - PetEncontra

## 📍 Endpoints

### 🔐 Autenticação
POST /login
POST /register

### 🐾 Pets
GET /pets
POST /pets
GET /pets/{id}

### ❤️ Adoção
POST /adocoes
GET /adocoes

## 📥 Exemplo Request
POST /pets
{
  "nome": "Rex",
  "idade": 2
}

## 📤 Exemplo Response
{
  "id": 1,
  "nome": "Rex"
}

## 🔐 Autenticação
JWT Token
