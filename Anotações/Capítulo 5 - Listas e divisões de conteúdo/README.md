# Neste capítulo vi sobre as listas ordenadas e não ordenadas, usando a tag ol, ul e li, o uso de class, de divs e como funciona os elementos inline e block.

Listas ordenadas e não ordenadas são usadas para listar itens. A tag ol é usada para listas ordenadas e a tag ul é usada para listas não ordenadas. A tag li é usada para cada item da lista.

As listas ordenadas são usadas para listar itens que possuem uma ordem. Por exemplo, uma lista de ingredientes de uma receita. Para criar ela no HTML, é necessário usar a tag ol e dentro dela, a tag li para cada item da lista.

```html
<ol>
  <li>Farinha</li>
  <li>Ovos</li>
  <li>Leite</li>
</ol>
```

As listas não ordenadas são usadas para listar itens que não possuem uma ordem. Por exemplo, uma lista de tarefas. Para criar ela no HTML, é necessário usar a tag ul e dentro dela, a tag li para cada item da lista.

```html
<ul>
  <li>Estudar HTML</li>
  <li>Estudar CSS</li>
  <li>Estudar JavaScript</li>
</ul>
```

## Usando class

Class é um atributo que é usado para identificar um elemento HTML. Ele pode ser repetido. O class é usado para estilizar um elemento HTML, sendo referenciado no CSS com o sinal de ".".

```html
<img class="logo" src="logo.png" alt="Logo da Alura" />
```

```css
.logo {
  width: 100px;
}
```

## Usando divs

Divs são usadas para dividir o conteúdo da página em seções. Elas são usadas para agrupar elementos HTML e para estilizar esses elementos.

```html
<div>
  <img class="logo" src="logo.png" alt="Logo da Alura" />
  <h1>Alura</h1>
</div>
```

## Elementos inline e block

Elementos inline são elementos que ficam um ao lado do outro. Elementos block são elementos que ficam um abaixo do outro.

```html
<p>Este é um parágrafo.</p>
<p>Este é outro parágrafo.</p>
```

```html
<div>Este é um bloco.</div>
<div>Este é outro bloco.</div>
```

O primeiro exemplo cria dois parágrafos, que são elementos inline, ou seja, ficam um ao lado do outro. O segundo exemplo cria dois blocos, que são elementos block, ou seja, ficam um abaixo do outro.
