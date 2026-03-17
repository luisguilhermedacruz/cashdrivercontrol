# 🚗 Cash Driver Control

Sistema web para controle financeiro de motoristas de aplicativo, permitindo registrar entradas, despesas e visualizar o lucro real de forma simples e organizada.

---

## 📌 Problema

Motoristas de aplicativo geralmente não têm clareza sobre seu lucro real.

Mesmo vendo quanto entra diariamente, é comum não saber:

- quanto foi gasto para gerar essa renda
- quanto realmente sobrou no final
- quais dias ou períodos são mais lucrativos

Isso acontece porque os dados ficam:

- espalhados
- não registrados
- ou difíceis de analisar

---

## 💡 Solução

O Cash Driver Control resolve esse problema permitindo:

- registro estruturado de entradas e despesas
- organização por categorias
- visualização clara de lucro
- análise simples por período

---

## 🚀 MVP (Minimum Viable Product)

O objetivo do MVP é resolver o problema principal com o menor conjunto de funcionalidades úteis.

### ✅ Funcionalidades incluídas

- Autenticação com Google  
- Cadastro de entradas (ganhos)  
- Cadastro de despesas  
- Listagem de transações  
- Filtro por período (dia, semana, mês)  
- Dashboard com:
  - total de entradas  
  - total de despesas  
  - lucro líquido  

---

### ❌ Fora do escopo do MVP

- Insights com IA  
- Análises avançadas  
- Importação automática de dados  
- Notificações  
- Relatórios complexos  

---

## 🧠 Conceitos aplicados

Este projeto foi construído com foco em aprendizado prático de engenharia de software:

- definição de problema antes da tecnologia
- construção de MVP enxuto
- modelagem de domínio (User, Transaction, Category)
- separação de responsabilidades (backend em camadas)
- arquitetura full stack moderna

---

## 🏗️ Arquitetura

### Backend
- Python
- FastAPI
- PostgreSQL

### Frontend
- React

### Autenticação
- Google OAuth

---

## 📂 Estrutura do projeto
cash-driver-control/
│
├── README.md
├── backend/
├── frontend/
└── docs/


---

## 🔄 Fluxo da aplicação

1. Usuário faz login com Google  
2. Backend valida e cria/busca usuário  
3. Usuário registra entradas e despesas  
4. Dados são armazenados no banco  
5. Dashboard exibe resumo financeiro  

---

## 🎯 Objetivo do projeto

Este projeto faz parte da minha transição para desenvolvimento backend com Python.

O foco é:

- aprender construindo um sistema real
- aplicar boas práticas de engenharia
- criar um portfólio sólido para vaga de desenvolvedor júnior

---

## 🧾 Próximos passos (futuro)

- análise de desempenho por período  
- identificação de melhores dias/horários  
- insights automáticos  
- uso de IA para recomendações  

---

## ⚙️ Como rodar o projeto

*(em construção)*

---

## 👨‍💻 Autor

Luis Guilherme da Cruz