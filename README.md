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

  ```
  html
  <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio / Curriculo Web</title>

    <style>
         th {
            background-color: #333; 
            color: white; 
        }
    </style>
</head>
<body style="background-color: #F2F0EF;">
    <header>
    <h1 style="color: #722F37;"><strong></strong> Miguel Augusto Porto Coutinho - Desenvolvedor Web</strong></h1>

        <nav>
    <ul>
        
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#projeto">Projetos</a></li>
        <li><a href="#contato">Contato </a></li>
    </ul>
    </nav>
    </header>
    <hr>
    <h2 id="sobre" style="color: #722F37;"><strong></strong> Sobre mim</strong></h2>
     <img src="foto.rosto.jpeg" alt=""foto" width="120" heigth="120">
     <p style="color: #722F37;"></pstyle>Estudante de Desenvolvimento de Sistemas no SENAI A. Jacob Lafer, com conhecimento <br> em lógica de programação e forte interesse no impacto da tecnologia na gestão e na eficiência operacional. <br> Ex-atleta de atletismo pelo SESI Santo André, trago do esporte a disciplina, o foco em metas e a busca por <br>constante superação no dia a dia técnico.</p>
     <p style="color: #722F37;"></pstyle>No curso de Desenvolvimento de Sistemas, estou aprendendo a projetar, construir e manter soluções <br> tecnológicas completas. Minha rotina de estudos envolve lógica de programação, desenvolvimento web <br> e back-end, modelagem de banco de dados e análise de requisitos. Mais do que escrever código, aprendo <br> a entender a necessidade do cliente e organizar o projeto para que o sistema ajude na eficiência do dia a dia da empresa.</p>
     <h3 style="color: #722F37;"><strong></strong> Minhas habilidades</strong></h3>
     <ul>
        
        <li>HTML5 Semântico</li>
        <li>CSS3 e Responsividade</li>
        <li>Formulários e Validação</li>
        <li>Estruturação de Dados</li>
    </ul>
<hr>
<h2 id="projeto" style="color: #722F37;"><strong></strong> Meus Projetos</strong></h2>
  <table border="1">
         <thead>
            <tr>
                <th>Projetos</th>
                <th>Tecnologias utilizadas</th>
                <th>Status</th>
                <th>Link</th>
            </tr>
         </thead>
          <tbody>
            <tr>
                <td>Semáfaro Inteligente</td>
                <td>Tinkercad/ C++, Arduino IDE, github, excel e flowgorithm</td>
                <td>Concluído</td>
                <td><a href="https://github.com/LoreeOliveira/Future_Techonology">Ver Projeto</a></td>
            </tr>
            <tr>
                <td>GamesRetro HTML5</td>
                <td>HTML5, Vscode e github</td>
                <td>Concluído</td>
                <td><a href="https://github.com/CoutomgPortinho/ATV_GameRetro">Ver Projeto</a></td>
            </tr>
            <tr>
                <td>Style Guide & Design System — Itaú</td>
                <td>Figma e Github</td>
                <td>Concluído</td>
                 <td><a href="https://github.com/CoutomgPortinho/ATV_identidadeIt-u">Ver Projeto</a></td>
            </tr>
          </tbody>
     </table>
     <hr>
     <h2 id="contato" style="color: #722F37;"><strong></strong> Entre em contato</strong></h2>
     <form>
     <fieldset>
    <legend>Dados do contato</legend>

    <label for="name">Nome: </label><br><br>
    <input type="text" name="nome"><br><br>

     <label for="email">e-mail: </label><br><br>
    <input type="email" name="email"><br><br>

    <label for="assunto">Assunto:</label><br>
<select name="assunto" id="assunto">
    <option value="oportunidade">Oportunidade de Trabalho</option>
    <option value="contato">Quero entrar em contato</option>
    <option value="projetos">Quero saber mais sobre os projetos</option>
</select><br><br>

     <label for="mensagem">Mensagem: </label><br><br>
    <textarea name="mensagem"></textarea>

    <button type="submit">Enviar</button>

     </fieldset>
    </form>
 
  <p> &copy; 2026 Meta. Desenvolvido durante o curso SENAI. </p>
  <hr>
<footer>
    <p><a href="miguel.a.coutinho@edu.senai.br">miguel.a.coutinho@edu.senai.br</a> | <a href="tel:+55 (11) 970302863">(11) 970302863</a></p>
</footer>

 

</body>
</html>

```


---

## 🛠️ Especificações Técnicas e Semântica

- **HTML5 Puro e Semântico**: Uso rigoroso de tags estruturais para acessibilidade e SEO (`<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<fieldset>`, `<footer>`).
- **Navegação por Âncoras**: Conexão entre o menu e as seções através de atributos `id`.
- **Formulários Acessíveis**: Todos os campos do formulário foram associados aos seus respectivos `<label>` usando os atributos `for` e `id`.
- **Dimensões de Mídia**: Foto de perfil padronizada via HTML com `width="150"` e `height="150"`.



Desenvolvido por **Seu Nome**  
Estudante de Desenvolvimento de Sistemas no SENAI A. Jacob Lafer.
