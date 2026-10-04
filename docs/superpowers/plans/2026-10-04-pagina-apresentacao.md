# Página de apresentação pessoal Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Criar uma página HTML simples e responsiva que apresente o trabalho de Rodolfo Coelho e facilite contato por e-mail.

**Architecture:** Um documento estático independente na raiz do repositório. A estrutura semântica e os estilos responsivos ficam no próprio HTML, sem JavaScript ou dependências.

**Tech Stack:** HTML5 e CSS embutido.

**Spec:** `docs/superpowers/specs/2026-10-04-pagina-apresentacao-design.md`

## Global Constraints

- Página em português, responsiva para celular e desktop.
- Apresentação breve e genérica, sem inventar detalhes profissionais.
- E-mail visível: `rodolfopc@gmail.com`.
- Link de contato: `mailto:rodolfopc@gmail.com`.
- Sem dependências ou JavaScript desnecessários.
- Incluir contraste legível e foco visível.

## Review Focus

- Tela estreita: conteúdo deve caber sem rolagem horizontal.
- Navegação por teclado: link de e-mail deve ter foco visível.
- Cliente sem estilos: conteúdo e contato permanecem compreensíveis pela semântica HTML.
- Acionamento do contato: endereço e destino `mailto:` devem coincidir exatamente.
- Dados biográficos ausentes: texto não deve atribuir serviços, experiência ou clientes não confirmados.

---

### Task 1: Criar a página de apresentação

**Files:**
- Create: `index.html`

**Interfaces:**
- Consumes: nenhum arquivo ou serviço externo.
- Produces: página estática acessível em `index.html`.

- [ ] **Step 1: Criar o documento HTML**

Adicionar estrutura HTML5 em português com metadados de charset e viewport, título, apresentação breve genérica e link de contato `mailto:rodolfopc@gmail.com`. Incluir CSS embutido com layout responsivo, cores de contraste legível e estado `:focus-visible` no link. Manter todo o texto visível sem depender de JavaScript.

- [ ] **Step 2: Conferir o documento e os requisitos**

Inspecionar `index.html` e confirmar que a estrutura está completa, o endereço aparece corretamente, o `mailto:` corresponde ao endereço e há regras para telas estreitas e foco visível. Não há suíte de testes nem build configurados no repositório.
