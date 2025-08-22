# Enterprise Architecture

Este repositório organiza a arquitetura de soluções corporativas com apoio de agentes de IA especializados. A estrutura modular cobre áreas como backend, frontend, DevOps, segurança, banco de dados, API Gateway, gestão ágil e visão de produto.

## Objetivo
Documentar decisões arquiteturais, facilitar colaboração e acelerar o desenvolvimento de sistemas empresariais.

## Estrutura
- backend-architect/
- frontend-architect/
- devops-infra/
- cybersecurity/
- database-specialist/
- api-gateway/
- agile-coach/
- product-owner/


# 📁 Convenção de Nomes de Repositórios - Projeto Enterprise Architecture

Este documento define o padrão de nomenclatura para os repositórios do projeto **Enterprise Architecture**, com foco em organização por **domínio funcional** e tipo de componente.

---

## 🔹 Convenção Recomendada

Formato geral:


- **Domínio**: área funcional (ex: `sales`, `inventory`, `finance`, `hr`) *utilizar siglas
- **Serviço**: nome do serviço (ex: `order`, `stock`, `billing`)
- **Tipo**:
  - `ms` para microsserviços
  - `portal` para frontends

---

## 🧩 Exemplos por Domínio

### 🛒 Vendas (`sales`)
- `sales-order-ms`
- `sales-customer-ms`
- `sales-portal`

### 📦 Estoque (`inventory`)
- `inventory-stock-ms`
- `inventory-supplier-ms`
- `inventory-portal`

### 💰 Financeiro (`finance`)
- `finance-payment-ms`
- `finance-billing-ms`
- `finance-portal`

### 👥 Recursos Humanos (`hr`)
- `hr-employee-ms`
- `hr-payroll-ms`
- `hr-portal`

---

## 🔐 Repositórios Compartilhados
- `shared-auth-ms`
- `shared-api-gateway`
- `shared-admin-portal`
- `shared-observability-stack`

---

Este padrão garante clareza, escalabilidade e organização entre os domínios funcionais da plataforma ERP.