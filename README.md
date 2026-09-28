# 💼 Portfólio / Currículo Web

Este projeto consiste na criação de uma página de **Portfólio / Currículo Web** desenvolvida com **HTML5 limpo e semântico**. O objetivo é demonstrar o domínio das boas práticas de estruturação web, organizando informações pessoais, habilidades, tabela de projetos e um formulário de contato funcional.

---

## 🎯 Objetivo do Desafio

Desenvolver uma página web responsiva, acessível e semântica que reproduza com precisão as seções, elementos e especificações do layout do modelo, garantindo uma navegação intuitiva através de links internos.

---

## 🚀 Funcionalidades e Estrutura do Projeto

A página foi construída respeitando rigorosamente a seguinte estrutura:

### 1. 📌 Cabeçalho & Navegação (`<header>` / `<nav>`)
- Título principal contendo Nome e Cargo.
- Menu de navegação superior com links de âncora (`href="#id"`) apontando para as seções: **Sobre**, **Projetos** e **Contato**.

### 2. 👤 Seção "Sobre Mim" (`<section id="sobre">`)
- Foto de perfil formatada nas dimensões exatas de **150px de altura × 150px de largura**.
- Texto explicativo de apresentação profissional.
- Lista estruturada com as **Minhas Habilidades**.

### 3. 📂 Seção "Meus Projetos" (`<section id="projetos">`)
- Tabela organizada (`<table>`) contendo **4 colunas**:
  - **Projeto**: Nome do projeto desenvolvido.
  - **Tecnologias**: Pilha de tecnologias utilizadas.
  - **Status**: Estado atual da aplicação (ex: Concluído, Em andamento).
  - **Link**: Hiperlink funcional redirecionando para a aplicação ou repositório.

### 4. 📬 Seção "Entre em Contato" (`<section id="contato">`)
- Formulário delimitado pela tag `<fieldset>` com o título **"Dados do Contato"** (`<legend>`).
- Campos de entrada associados a elementos `<label>` vinculados devidamente:
  - Nome completo
  - E-mail
  - Menu suspenso (`<select>`) para seleção do **Assunto**
  - Área de texto (`<textarea>`) para digitação da **Mensagem**
- Botão de envio (`<button type="submit">`).

### 5. 🦶 Rodapé (`<footer>`)
- Informações de Direitos Autorais utilizando a entidade especial de HTML (`&copy;`).
- Dados para contato direto (e-mail e telefone).

---

## 🛠️ Especificações Técnicas e Semântica

- **HTML5 Puro e Semântico**: Uso rigoroso de tags estruturais para acessibilidade e SEO (`<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<fieldset>`, `<footer>`).
- **Navegação por Âncoras**: Conexão entre o menu e as seções através de atributos `id`.
- **Formulários Acessíveis**: Todos os campos do formulário foram associados aos seus respectivos `<label>` usando os atributos `for` e `id`.
- **Dimensões de Mídia**: Foto de perfil padronizada via HTML com `width="150"` e `height="150"`.



Desenvolvido por **Seu Nome**  
Estudante de Desenvolvimento de Sistemas no SENAI A. Jacob Lafer.
