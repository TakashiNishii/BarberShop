# Nesse capítulo vi sobre o que é CSS e como ele funciona, além de aprender a usar o CSS no HTML.

O CSS (Cascade Style Sheets) é uma linguagem de estilo que serve para estilizar o HTML. Ele é usado para definir cores, fontes, espaçamentos, entre outras coisas.
O CSS pode ser utilizado de 3 formas:

- Inline: Usando a tag style dentro da tag HTML.

Exemplo:

```html
<p style="color: red">Texto</p>
```

- Interno: Usando a tag style dentro da tag head.

Exemplo:

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
```

- Externo: Criando um arquivo CSS e linkando ele no HTML.

Nesse caso você cria um arquivo chamado style.css e coloca a sua estilização nele. Depois você linka esse arquivo no HTML como mostra no exemplo abaixo.

Exemplo:

```html
<head>
  <link rel="stylesheet" href="style.css" />
  <!-- Linkando o arquivo style.css -->
</head>
```

Para estilizar um elemento especifico, podemos utilizar a estrutura do html, como mostra o exemplo abaixo.

Exemplo:

```html
<head>
  <style>
    body p {
      /* Estilizando todos os parágrafos dentro do body */
      color: red;
    }
  </style>
</head>
```

## Como funciona a coloração do CSS

A coloração do CSS funciona da seguinte forma:

- RGB: Red, Green, Blue. Cada cor é representada por um número de 0 a 255. Exemplo: rgb(255, 0, 0) é vermelho.
- HEX: Cada cor é representada por um número de 0 a F. Exemplo: #FF0000 é vermelho.
- Nome: Cada cor tem um nome. Exemplo: red é vermelho.
