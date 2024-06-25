# Introdução ao HTML, CSS e JavaScript

HTML, CSS e JavaScript são três das tecnologias mais importantes da web. Elas são frequentemente usadas juntas para criar páginas web interativas e esteticamente agradáveis. Vamos explorar cada uma delas, entender suas funções e ver alguns exemplos simples.

## O que é HTML?

HTML (HyperText Markup Language) é a linguagem padrão usada para criar e estruturar conteúdo na web. Ela define a estrutura básica de uma página web utilizando uma série de elementos ou tags.
Exemplo Simples de HTML:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de HTML</title>
</head>
<body>
    <h1>Olá, Mundo!</h1>
    <p>Este é um exemplo simples de uma página HTML.</p>
</body>
</html>

```

**Principais Tags do HTML:**

* `<html>`: Define o documento HTML.
* `<head>`: Contém metadados sobre o documento.
* `<title>`: Define o título da página (aparece na aba do navegador).
* `<body>`: Contém o conteúdo visível da página.
* `<h1>` a `<h6>`: Definem títulos, sendo `<h1>` o mais importante e `<h6>` o menos importante.
* `<p>`: Define um parágrafo.
* `<a>`: Define um hyperlink.
* `<img>`: Insere uma imagem.
* `<div>`: Define uma seção ou um contêiner genérico.

## O que é CSS?

CSS (Cascading Style Sheets) é uma linguagem de estilo usada para descrever a apresentação de um documento HTML. Ele controla a aparência dos elementos HTML, como cores, fontes, espaçamentos e layout.

**Exemplo Simples de CSS:**


```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de CSS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        h1 {
            color: blue;
        }
        p {
            font-size: 16px;
            color: green;
        }
    </style>
</head>
<body>
    <h1>Olá, Mundo!</h1>
    <p>Este é um exemplo simples de uso de CSS.</p>
</body>
</html>
```

**Principais Informações do CSS:**

* `color`: Define a cor do texto.
* `font-family`: Define a fonte do texto.
* `font-size`: Define o tamanho da fonte.
* `background-color`: Define a cor de fundo de um elemento.
* `margin`: Define a margem externa de um elemento.
* `padding`: Define o espaçamento interno de um elemento.
* `border`: Define a borda de um elemento.

## O que é JavaScript?

JavaScript é uma linguagem de programação que permite adicionar interatividade às páginas web. Ele pode alterar o conteúdo e o estilo dos elementos HTML em resposta a eventos do usuário, como cliques ou entradas de formulário.
Exemplo Simples de JavaScript:

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de JavaScript</title>
</head>
<body>
    <h1>Olá, Mundo!</h1>
    <p id="paragrafo">Este é um exemplo simples de uso de JavaScript.</p>
    <button onclick="mudarTexto()">Clique aqui</button>

    <script>
        function mudarTexto() {
            document.getElementById('paragrafo').innerText = 'O texto foi alterado!';
        }
    </script>
</body>
</html>
```

**O Básico do JavaScript:**

* `document.getElementById('id')`: Seleciona um elemento pelo seu ID.
* `innerText`: Propriedade que define ou obtém o texto interno de um elemento.
* `function nomeDaFuncao() { ... }`: Declara uma função.
* `onclick`: Atributo HTML que executa JavaScript quando o elemento é clicado.

Perguntas de Múltipla Escolha

    Qual é a principal função do HTML?
        a) Estilizar elementos da página
        b) Adicionar interatividade à página
        c) Estruturar o conteúdo da página
        d) Executar scripts no servidor

    Resposta: c) Estruturar o conteúdo da página

    Qual tag HTML é usada para definir um parágrafo?
        a) <p>
        b) <div>
        c) <a>
        d) <h1>

    Resposta: a) <p>

    Qual propriedade CSS é usada para definir a cor de fundo de um elemento?
        a) color
        b) background-color
        c) font-size
        d) border

    Resposta: b) background-color

    O que o código document.getElementById('paragrafo').innerText faz em JavaScript?
        a) Seleciona um elemento pelo seu nome de classe
        b) Altera o estilo de um elemento
        c) Seleciona um elemento pelo seu ID e altera seu texto interno
        d) Adiciona uma nova função ao documento

    Resposta: c) Seleciona um elemento pelo seu ID e altera seu texto interno

    Qual das seguintes opções é um exemplo de uma função em JavaScript?
        a) <button onclick="mudarTexto()">Clique aqui</button>
        b) function mudarTexto() { ... }
        c) color: blue;
        d) <h1>Olá, Mundo!</h1>

    Resposta: b) function mudarTexto() { ... }

Essas perguntas cobrem os conceitos básicos discutidos no artigo e ajudam a reforçar o entendimento sobre HTML, CSS e JavaScript.