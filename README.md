# Manual de T.I. - Central de Serviços Compartilhados Neural

Este repositório contém o código-fonte do **Manual de Arquitetura e Procedimentos de T.I.** da Central de Serviços Compartilhados Neural (Grupo Elo). 

O sistema foi desenvolvido em formato *Single-Page Application* (SPA) utilizando HTML, CSS e JavaScript puros, agrupados em um único arquivo. Isso garante um carregamento extremamente leve, performance fluida e elimina a necessidade de infraestrutura complexa ou servidores backend.

## 🚀 Visão Geral

O principal objetivo deste manual é atuar como o guia definitivo e centralizado de referência para todos os membros da equipe de Tecnologia, desde a linha de frente do atendimento até a gestão de infraestrutura complexa. 

O conteúdo do manual engloba:
- **Estrutura Organizacional**: Mapeamento do Suporte N1 (Helpdesk, Fieldservice, Servicedesk, Gestão de Acessos) e Suporte N2 (Infraestrutura, Redes, Segurança da Informação, Telecom).
- **Grupos de Trabalho**: Comunicação facilitada, direcionamentos para eventos críticos, etc.
- **Ferramentas e Sistemas**: Acesso rápido a sistemas de operações, portais parceiros e ferramentas essenciais do dia a dia.
- **Processos (Ex: GLPI e Fluxo Home Office)**: Diretrizes e fluxogramas operacionais para conduzir solicitações rotineiras da melhor forma ágil.

## 💻 Tecnologias

Foi implementado com tecnologias web essenciais, com foco em uma interface de usuário (UI) moderna (com Glassmorphism e Dark Theme), fluida, e responsiva:

- **HTML5**
- **CSS3** (Recursos modernos: Custom Properties, Flexbox, CSS Grid, Keyframes/Animações)
- **JavaScript Vanilla** (Controle de Modais, Sistema de Tabs, Buscas em tempo real, Toggle da Sidebar)
- **Font Awesome 6.1.1** (Iconografia digital)
- **Google Fonts** (Tipografias *Outfit* e *Inter*)

## 📂 Estrutura do Projeto

Para garantir total consistência e não depender de roteamento ou carregamento de diferentes rotas ou arquivos `assets`, o projeto consolida tudo internamente:

- `index.html`: Arquivo central da aplicação que acopla toda a marcação `HTML`, o escopo global de `CSS` e todo o script interativo do `JavaScript`.

## 🛠️ Como Executar Localmente

Sendo uma página totalmente estática *Client-Side* sem dependências *Node.js* ou configurações de *bundlers* (como Vite/Webpack):

1. Clone o repositório na sua máquina:
   ```bash
   git clone https://github.com/grupoeloslz/manual-ti.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd manual-ti
   ```
3. Dê um duplo-clique no arquivo `index.html` ou abra ele no seu navegador favorito (Google Chrome, Edge, Firefox, Safari).

---
*Desenvolvido pela Equipe de Tecnologia Neural*
