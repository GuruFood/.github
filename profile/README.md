# 🍔 GuruFood Platform

> Ecossistema completo para operação, gestão e expansão do GuruFood.

---

## 📦 Repositórios da Plataforma

### 🧠 Core Services

| Repositório | Descrição |
|---|---|
| `gurufood-api-service` | API principal do sistema operacional |
| `gurufood-auth-service` | Serviço de autenticação do sistema |
| `gurufood-admin-api-service` | API da plataforma administrativa |
| `gurufood-admin-auth-service` | Serviço de autenticação do portal administrativo |

---

### 💻 Frontends

| Repositório | Descrição |
|---|---|
| `gurufood-web` | Painel operacional web em Next.js |
| `gurufood-admin-web` | Portal administrativo interno |
| `gurufood-pdv-android` | Aplicativo Android do PDV/SmartPOS |

---

### 🗄️ Infraestrutura & Banco

| Repositório | Descrição |
|---|---|
| `gurufood-infra` | Docker, Kong Gateway, compose, observabilidade e infraestrutura |
| `gurufood-db` | Estrutura de banco de dados e migrations Flyway |

---

### 📚 Documentação

| Repositório | Descrição |
|---|---|
| `gurufood-api-docs` | Collections Bruno, documentação e contratos das APIs |

---

# 🏗️ Arquitetura

```txt
Clients
 ├── Web Operacional
 ├── Admin Web
 └── Android PDV

Gateway
 └── Kong API Gateway

Services
 ├── Auth Service
 ├── Admin Auth Service
 ├── API Service
 └── Admin API Service

Data Layer
 ├── PostgreSQL
 ├── Redis
 └── Flyway
```

## 🚀 Stack Tecnológica

### Backend
- Java / Spring Boot
- JWT Authentication
- PostgreSQL
- Redis
- Flyway

### Frontend
- Next.js
- React
- TailwindCSS

### Mobile
- Kotlin Android
- SmartPOS Integration

### Infraestrutura
- Docker
- Docker Compose
- Kong Gateway
- Observabilidade

## 🔐 Padrões da Plataforma

- Arquitetura orientada a serviços
- APIs REST versionadas
- JWT Authentication
- Multiempresa (multi-tenant)
- Controle granular de permissões
- Estrutura preparada para expansão nacional
- CI/CD ready
- Infraestrutura containerizada

## 📖 Convenções

### Branches
- `main`
- `develop`
- `feature/*`
- `hotfix/*`
- `release/*`

### Commits

Padrão baseado em Conventional Commits:

- `feat:`
- `fix:`
- `refactor:`
- `chore:`
- `docs:`
- `test:`

## ☕ Visão

O GuruFood está sendo construído para ser uma plataforma moderna de operação para restaurantes, cafeterias e negócios gastronômicos, unindo tecnologia, performance operacional e experiência.

## 👨‍💻 Organização

Este repositório `.github` centraliza:

- templates
- padrões
- documentação organizacional
- onboarding
- convenções da plataforma
- health files do GitHub
