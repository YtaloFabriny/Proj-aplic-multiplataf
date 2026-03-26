# 🗄️ Modelo de Dados

## 📌 Entidades

### Usuário
- id
- nome
- email
- senha

### Pet
- id
- nome
- idade
- descrição
- status

### Adoção
- id
- usuario_id
- pet_id
- status

## 🔗 Relacionamentos
- Usuário 1:N Adoção
- Pet 1:1 Adoção

## 📖 Dicionário de Dados
- status_pet: disponível, adotado
- status_adoção: pendente, aprovado, rejeitado
