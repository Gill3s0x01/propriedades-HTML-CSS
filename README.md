<h1 align="center">
  <p align="center">
    <img alt="HTML-CSS" src="./transferir.jpg" width="350px" height="auto"/>
  </p>
  <h3 align="center">
    Uma maneira explicação de fácil entendimento, propriedades HTML e CSS.
  </h3>
  </p>
  <p align="center">
      <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/Gilles30/propriedades-HTML-CSS?color=1db954">
      <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Gilles30/propriedades-HTML-CSS?color=1db954">
      <img alt="Stars" src="https://img.shields.io/github/stars/Gilles30/propriedades-HTML-CSS?color=1db954">
      <img alt="Repository Size" src="https://img.shields.io/github/repo-size/Gilles30/propriedades-HTML-CSS?color=1db954">
  </p>
</h1>

<p align="center">
  <a href="#page_with_curl-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#books-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-começando">Começando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-HTML">HTML</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-Principais Propriedades do CSS">Principais Propriedades do CSS</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## Propriedades HTML e CSS

## :page_with_curl: Sobre


Neste Readme apresento algumas das principais propriedades do HTML e CSS, espeo que esse doc ajude muitas pessoas que estão começando.

## :books: Requisitos
- Ter [**Git**](https://git-scm.com/) para clonar o projeto.
- Ter [**Node.js**](https://nodejs.org/en/) instalado.
- Ter [**Yarn**](https://classic.yarnpkg.com/pt-BR/docs/install/) instalado.

## :rocket: 🎧🕹Começando
``` bash
  # Clonar o projeto:
  $ git clone https://github.com/Gilles30/skylabnext-codedrops-48

  # Entrar no diretório:
  $ cd propriedades-HTML-CSS
  
```

## :gear: HTML

```bash
  ## Elemento Raiz:
  $ <html> ... </html>

  # Elementos não visuais dentro do head:
  $ <head> ... </head> //Meta dados

  # Estilo interno. De preferência, adicione estilos externos!:
  $ <style> ... </style>
  
  ## Elementos não visuais dentro do head:
  $ <head> ... </head> //Meta dados
  
  # Código javascript (pode estar dentro do body também):
  $ <script> ... </script>
  
  # Estilo externo:
  $ <link rel="stylesheet" href = "style.css"/>
  
  # Título da página:
  $ <title> ... </title>
  
  # Informações do documento (pode ter autor, descrição, entre outros...):
  $ <meta charset="utf-8">
  
  ## Elementos não visuais dentro do body:
  $ <body> ... </body> //Corpo do documento
  
  # Bloco genérico :
  $ <div> ... </div>
  
  # Bloco do contúdo:
  $ <section> ... </section>
  
  # Conteúdo repetitível (artigo, post...):
  $ <article> ... </article>
  
  # Sidebar / barra lateral:
  $ <aside> ... </aside>
  
  # Cabeçalho:
  $ <header> ... </header>
  
  # Rodapé:
  $ <footer> ... </footer>
  
  # Bloco de navegação. Ex: menus:
  $ <main> ... </main>
  
  ## Elemento visuais de lista:
  $ <ul> ... </ul> // Lista não ordenada
  
  # Lista ordenada (1, 2, 3...):
  $ <ol> ... </ol>
  
  # Elemento unico da lista:
  $ <li> ... </li>
  
  ## Elementos visuais de multimidia:
  $ <img src="imagem.jpg"/> //Imagem
  
  # Video:
  $ <Imviagdeemo src="video.ogg"/>
  
  ## Elementos visuais de texto:
  $ <em> ... </em> //Texto em itálico com ênfase
  
  # Texto genérico:
  $ <span> ... </span>
  
  # Link:
  $ <a href="google.com.br"> ... </a>
  
  ## Tabela:
  $ <table> ... </table> // Estrutura da tabela
  
  # Linha da tabela:
  $ <tr> ... </tr>
  
  
  # Coluna da tabela:
  $ <td> ... </td>
  
  # Título da coluna:
  $ <td> ... </td>
  
  
  ## Elementos visuais de formulário:
  $ <form> ... </form> // Estrutura do formulário
  
  
  # Define um campo de entrada //text, number, date, file, checkbox, email, radio, password...:
  $ <input type="">
  
  # Área de texto:
  $ <textarea> ... </textarea>
  
  # Botão:
  $ <button> ... </button>
  
  # Drop - Down:
  $ <select> ... </select>
  
  # Lista de opções dentro de um drop-down:
  $ <option> ... </option>
  
  # Grupo de campos:
  $ <fieldset> ... </fieldset>
  
  # Legenda para um campo:
  $ <label> ... </label>
  
  
  
```

## :computer: Principais Propriedades do CSS
```bash
  # EImagem de fundo:
  $ background-color: #FFFFF // Cor de fundo

  # Instalar as dependências:
  $ background-image: url(image.png)

  # Posição da imagem do fundo:
  $ background-position: center
  
  # Define se a imagem do fundo deve repetir ou não:
  $ background-repeat: no-repeat //Atalho para múltiplos propriedades
  
  
  ## Propriedades de fonte:
  $ font-size: 20px ou 0.2em, 2rem, 50%... //Tamanho do texto
  
  
  # Peso do texto:
  $ font-weight: bold, normal, 300, 500..
  
  
  ## Propriedades de texto:
  $ font: 20px sans-serif bold //Multiplas propriedades
  
  # Cor do texto:
  $ color: #FFFFF
  
  
  # Tamanho da linha:
  $ line-height: 26px
  
  
  # Espaçamento de cada caractere:
  $ letter-spacing: 2px
  
  
  # Alinhamento horizontal do texto:
  $ text-align: center
  
  # Aplica decoração ao texto:
  $ text-decoration: underline
  
  ## Propriedades de espaçamento:
  $ padding: 20px //Espaçamento interno 20px em todos os lados:
  
  # 10px vertical 20px horizontal:
  $ padding: 10px 20px
  
  #10px topo 20px horizontal - 30px abaixo:
  $ padding: 10px 20px 30px
  
  # 10px topo - 20px direito 30px abaixo - 40px esquerda:
  $ padding: 10px 20px 30px 40px
  
  
  # Espaçamento externo Mesma regra de padding:
  $ margin: 10px 20px
  
  ## Propriedades de exibição:
  $ display: block // Tipo de exibição
  
  ## Tipos de display:
  $ block // O elemento se comporta como um bloco (ocupa largura total)
  
  # Ocupa apenas o espaço necessário dentro da linha:
  $ inline
  
  # O elemento se comporta como um container flexível:
  $ flex
  
  
  # O elemento se comporta como grid:
  $ grid
  
  # O elemento não é exibido na tela:
  $ none
  
  ## Propriedades de exibição:]
  
  $ opacity: 0.5
  # Opacidade do elemento (0 até 1)

  $ width: 100px
  # Largura do elemento

  $ min-width: 50px
  # Largura mínima

  $ max-width: 250px
  # Largura máxima

  $ height: 100px
  # Altura do elemento

  min-height e max-height também se aplica! position: absolute


  Como o elemento se posiciona em relação ao pai

  $ position: relative
  # Elemento relativo ao pai

  $ position: absolute
  # Torna o elemento flutuante em relação ao elemento relativo
  
  ## Propriedades de exibição:
  
  $ position: fixed
  # Torna o elemento fixo

  $ border: 1px solid black
  # Tamanho, estilo e cor da borda

  ## Estilos:
  $ solid
  $ dashed
  $ dotted
  $ double

  $ border-radius: 8px
  # Arredondamento das bordas

  
```

Feito com 💜 por [Lorison Gilles](https://www.linkedin.com/in/lorison-gilles/) 🖖🏻👾☕

### Resultado esperado

Ajudar os dev iniciantes com um material de facil entendimento e consulta.
