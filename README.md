# Site de Apresentação de Portfólio do Grupo

Projeto desenvolvido para a disciplina de **Front-End e Frameworks** do curso de Análise e Desenvolvimento de Sistemas (2º Período).

**Professor:** George Alberto Ferreira Cavalcante
**Data de Entrega:** 11/12/2025

---

## 📝 Descrição do Projeto
Este projeto consiste num site responsivo para apresentação do portfólio do grupo. O objetivo principal foi a aplicação prática do framework **Bootstrap 5**, focando na utilização correta do sistema de grid (grades), componentes e semântica HTML.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estrutura semântica (Header, Main, Section, Footer).
* **CSS3:** Estilização personalizada e animações de hover.
* **Bootstrap 5 (CDN):** Framework base para responsividade e componentes.

---

## ⚙️ Estrutura do Projeto (Requisitos Técnicos)

A estrutura do projeto foi organizada seguindo rigorosamente as regras solicitadas:

### 1. Organização de Pastas
```text
/Portfolio_Grupo
│
├── index.html        # Arquivo principal
├── README.md         # Documentação do projeto
├── css/
│   └── style.css     # Estilos personalizados (sobrescrevendo Bootstrap)
├── img/              # Imagens dos membros e projetos
└── js/               # Scripts adicionais (se houver)
```
### 2. O Sistema de Grid (3x4)
Para atender à exigência de 3 colunas por linha e 4 linhas no total dentro da tag ```<main>```, utilizou-se a seguinte lógica matemática do Bootstrap:

* Grid Total: 12 colunas.

* Cálculo: 12 dividido por 3 cards = 4.


Desta forma, garantimos visualmente 3 cards por linha em telas médias e grandes, totalizando 12 seções de conteúdo (Projetos, Membros, Serviços e Informações).

### 3. Componentes Bootstrap Utilizados
* Navbar: Para navegação responsiva no cabeçalho.

* Cards: Para estruturar o conteúdo de forma modular na área principal.

* Buttons: Para chamadas de ação (CTAs) e links.

* Grid System: Para o layout principal.

---
