# 🚀 docker-secure-api

API segura construída com Node.js e Express, empacotada com Docker usando boas práticas de produção, controle de rede e segurança.

## 📌 Objetivo

Demonstrar como criar um servidor seguro com Docker rodando uma API simples, utilizando:

- `Dockerfile` com boas práticas
- `docker-compose` para gerenciamento de containers
- Rede isolada com `docker network create`
- Controle de permissões no container
- Deploy local seguro e reproduzível

## 🛠️ Tecnologias Utilizadas

- Node.js + Express
- Docker
- Docker Compose

---

## 🧪 Como executar localmente com Docker

### 1. Clone o repositório

```bash
git clone https://github.com/Rma98/docker-secure-api.git
cd docker-secure-api
```

### 2. Suba a API com Docker Compose

```bash
docker compose up --build -d
```

### 3. Acesse a aplicação

Abra o navegador e acesse:

```
http://localhost:3000
```

Você verá a mensagem:

```
API segura rodando com Docker!
```

---

## 🔐 Segurança e boas práticas aplicadas

- Porta configurada via variável de ambiente
- Container isolado em rede própria
- Sem root no Docker (em breve)
- Arquivos desnecessários ignorados com `.dockerignore`
- `node_modules/` fora do Git

---

## 📄 Licença

Este projeto é apenas educacional e feito com 💙 por Robson Albuquerque.

---

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Plataforma](https://img.shields.io/badge/Plataforma-Localhost-blue)
![Linguagem](https://img.shields.io/github/languages/top/Rma98/docker-secure-api)
![Último commit](https://img.shields.io/github/last-commit/Rma98/docker-secure-api)
