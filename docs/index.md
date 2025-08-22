# Documentação do Projeto Enterprise Architecture

Bem-vindo à documentação centralizada do projeto.

# Enterprise Architecture

Este documento descreve a arquitetura do projeto **Enterprise Architecture**, conforme definido por Eduardo Moser.

---

## 🧱 Arquitetura Geral

### 🖥️ Frontend
- **Next.js** com comunicação via **REST**
- Autenticação com **Auth0** (JWT)
- Deploy em **AKS** como container

### ⚙️ Backend
- **Node.js + Express**
- Estrutura modular por serviço (sem DDD)
- Comunicação com MongoDB via **Mongoose**
- Cada serviço em seu próprio container
- Comunicação entre serviços via **REST**
- Deploy em **AKS**

### 🗃️ Banco de Dados
- **MongoDB Atlas**

### 🔐 Segurança
- Autenticação via **JWT**
- Gerenciamento de segredos com **Azure Key Vault (AKV)**

### 📊 Observabilidade
- **Prometheus** + **Grafana**
- **Azure Monitor** + **Application Insights**
- **OpenTelemetry** para métricas e rastreamento

### 🚪 API Gateway
- **Azure API Management**

### 🚀 DevOps
- CI/CD com **GitHub Actions**
- Infraestrutura como código com **Terraform** ou **Bicep**

---

## 📌 Diagrama Visual

![Arquitetura Enterprise Architecture](RandomFileName_ae135c4d-1209-4d77-96f1-82cc9ceac902.png)