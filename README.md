# API Marketplace de Veículos (.NET / C#)

Este projeto tem como objetivo **migrar a API existente em Node.js** para **.NET e C#**, mantendo e expandindo suas funcionalidades.  
A API será responsável por fornecer dados de veículos de um **marketplace**, consumindo informações armazenadas no **Firebase**.

---

## 🎯 Escopo Inicial

- Criar estrutura base do projeto em **.NET 6+ / C#**.  
- Implementar rotas principais:  
  - `GET /vehicles` → retorna todos os veículos (getAll).  
  - `GET /vehicles/{id}` → retorna um veículo pelo ID (getById).  
  - `GET /vehicles/slug/{slug}` → retorna um veículo pelo slug (getBySlug).  
- Integração com **Firebase** como banco de dados.  

---

## 📌 Evoluções previstas

- Novas rotas e filtros de busca.  
- Autenticação e autorização de usuários.  
- Deploy em nuvem (GCP). 
