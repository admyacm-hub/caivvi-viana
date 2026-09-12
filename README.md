# 🏛️ CAIVVI — Centro Integrado de Apoio a Vítima de Violência de Viana

> **Acolher • Proteger • Apoiar • Resgatar**
> _"Por uma sociedade mais segura, justa e sem violência"_

Portal web institucional do **CAIVVI**, com portal público para a comunidade e painel administrativo interno para gestão de atendimentos.

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Instalação e Uso](#-instalação-e-uso)
- [Credenciais de Acesso](#-credenciais-de-acesso)
- [Segurança](#-segurança)
- [Acessibilidade](#-acessibilidade)
- [Publicação (GitHub Pages)](#-publicação-github-pages)
- [Manutenção](#-manutenção)
- [Licença](#-licença)
- [Contactos](#-contactos)

---

## 🎯 Sobre o Projeto

O **CAIVVI** (Centro Integrado de Apoio a Vítima de Violência de Viana) é uma instituição dedicada ao apoio, proteção e orientação de vítimas de violência no Município de Viana, Luanda, Angola.

Este projeto consiste em:

- 🌐 **Portal Público** — Informação institucional, tipologias de violência, serviços e formulário de denúncia confidencial
- 🔒 **Painel do Gestor** — Sistema interno de gestão de atendimentos com dashboard, estatísticas e exportação de dados
- 📄 **Caderno de Encargos** — Documento formal com especificações técnicas e orçamento

### Enquadramento Legal

- **Lei 25/11 de 14 de julho** — Lei contra a Violência Doméstica (Angola)
- Constituição da República de Angola
- Legislação sobre Proteção de Dados Pessoais
- Normas de Acessibilidade Web (WCAG 2.1)

---

## ⚡ Funcionalidades

### Portal Público

- ✅ Página inicial com hero institucional
- ✅ Secção "Sobre" com missão e enquadramento legal
- ✅ 6 tipologias de violência (física, psicológica, verbal, patrimonial, sexual, abandono)
- ✅ 4 serviços principais (jurídico, psicológico, mediação, proteção)
- ✅ Formulário de denúncia confidencial com validação
- ✅ Contactos diretos (telefone, WhatsApp, email)
- ✅ **Saída rápida (tecla ESC)** — segurança da vítima
- ✅ Design responsivo (desktop, tablet, mobile)
- ✅ Menu mobile hamburger
- ✅ Botão "voltar ao topo"

### Painel do Gestor

- ✅ Login com autenticação
- ✅ Dashboard com métricas em tempo real
- ✅ Gráficos interativos (Chart.js) — categorias e evolução temporal
- ✅ Filtros temporais (dia, semana, mês, trimestre, semestre, ano)
- ✅ Filtros por categoria
- ✅ CRUD completo de registos (criar, ler, atualizar, apagar)
- ✅ Busca por nome ou contacto
- ✅ Exportação em CSV e JSON
- ✅ Persistência local com `localStorage`
- ✅ Interface responsiva

---

## 🛠️ Tecnologias

| Categoria | Tecnologia | Versão |
|---|---|---|
| Frontend | HTML5 | Latest |
| Frontend | CSS3 | Latest |
| Frontend | JavaScript | ES6+ |
| Gráficos | [Chart.js](https://www.chartjs.org/) | 4.4.0 |
| Ícones | [Font Awesome](https://fontawesome.com/) | 6.4.0 |
| Fontes | [Google Fonts](https://fonts.google.com/) | Montserrat, Lato |
| Armazenamento | Web Storage API | localStorage |
| Hospedagem | GitHub Pages | — |

> ⚙️ **Nota:** O projeto é 100% frontend estático. Não requer backend, base de dados ou servidor próprio. Os dados do painel são armazenados localmente no navegador (`localStorage`).

---

## 📁 Estrutura do Projeto
