# Checklist – Sprint 2 

📅 Data: 27/05/2026   
👥 Equipe: Grêmio Digital

**Integrantes:** Fred Gabriel, Giovani Silva, Lucas de Jesus, Gustavo Barbosa, Guilherme Krinski

---

## 1. Revisão da Sprint 1

- [x] Conferir entregáveis da Sprint anterior
  - Plano de Projeto ✅
  - Documento de Visão ✅
  - Documento de Requisitos (RF01–RF05, RNF01–RNF05) ✅
  - Backlog do Produto (20 US + 5 RNF no GitHub Projects) ✅
  - Protótipo navegável no Figma ✅
  - Daily Scrum registrada em `docs/daily-scrum-20-05-2026.md` ✅
- [x] Identificar pontos de melhoria
  - Definição técnica detalhada (stack e padrões) ainda não formalizada → **objetivo desta Sprint**

---

## 2. Definição Técnica

- [x] Escolher linguagem e frameworks
  - Frontend: **React.js + Tailwind CSS**
  - Backend: **Node.js + Express**
- [x] Definir arquitetura
  - Arquitetura **Cliente-Servidor** com **API REST**
  - Padrão **MVC adaptado**: Model (Firebase), View (React), Controller (Express)
- [x] Estabelecer padrões de código
  - Nomenclatura: `camelCase` (variáveis), `PascalCase` (componentes), `kebab-case` (arquivos)
  - Commits: Conventional Commits (`feat:`, `fix:`, `docs:`, `refactor:`)
  - Branches: `main` → `develop` → `feature/nome-da-feature`
- [x] Selecionar ferramentas de apoio
  - Versionamento: **GitHub**
  - Banco de dados: **Firebase Firestore**
  - Autenticação: **Firebase Auth**
  - Hospedagem: **Vercel** (Free Tier)
  - Revisão de código: **Pull Requests** com revisão por par

---

## 3. Implementação Incremental

- [x] Selecionar histórias de usuário para Sprint 2
  - US07 – Criar e gerenciar pautas de votação
  - US08 – Painel administrativo com login protegido
  - US09 – Dashboard de resultados em tempo real
  - US12 – Confirmação visual após votar
- [x] Criar tarefas detalhadas
  - Ver detalhamento em Documento Técnico 🔗 [Documentação do Projeto](https://gremiodigital-documentacao.netlify.app/)
- [x] Trabalhar em pares (Pair Programming)
  - Par 1: Giovani (Driver) + Fred (Navigator) → US07
  - Par 2: Fred (Driver) + Giovani (Navigator) → US08
  - Par 3: Lucas (Driver) + Gustavo (Navigator) → US09
  - Par 4: Fred (Driver) + Lucas (Navigator) → US12
- [ ] Codificar novas funcionalidades *(a realizar no PI II)*
- [ ] Realizar testes básicos *(a realizar no PI II)*

---

## 4. Protótipo Funcional

- [x] Atualizar protótipo com incremento da Sprint 2
  - Tela de login do administrador
  - Formulário de criação de pauta
  - Dashboard de resultados em tempo real
  - Tela de confirmação visual após votar
  - 🔗 [Acessar protótipo no Figma](https://sharp-set-73507180.figma.site/login)
- [x] Validar funcionalidades implementadas
  - Protótipo validado com representantes do Grêmio Estudantil (CEM Paulo Freire)
- [x] Documentar decisões técnicas
  - Ver seção 5 do documento técnico

---

## 5. Entrega Parcial

- [x] Publicar protótipo funcional no repositório
  - 🔗 [Repositório GitHub](https://github.com/Jhovannyz/Projeto-Integrador-I/tree/main)
- [x] Adicionar o checklist-sprint2 em `docs/sprint2/`
  - `docs/sprint2/checklist-sprint2.md` ✅
- [x] Adicionar o Documento Técnico no site da documentação central
  - 🔗 [Documentação do Projeto](https://gremiodigital-documentacao.netlify.app/) ✅
- [x] Atualizar quadro no GitHub Projects
  - US07, US08, US09 e US12 movidas para **🔄 In Progress**
  - 🔗 [Acessar GitHub Projects](https://github.com/Jhovannyz/Projeto-Integrador-I/projects)

---

## 📊 Resumo da Sprint 2

| Item | Status |
|---|---|
| Revisão da Sprint 1 | ✅ Concluído |
| Definição técnica (stack, arquitetura, padrões) | ✅ Concluído |
| Histórias selecionadas e detalhadas | ✅ Concluído |
| Pair Programming aplicado | ✅ Realizado |
| Protótipo atualizado | ✅ Concluído |
| Documento técnico entregue | ✅ Concluído |
| GitHub Projects atualizado | ✅ Concluído |

---
