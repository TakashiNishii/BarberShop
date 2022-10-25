# Nesse capítulo vi sobre os eventos do CSS e de como fazer para mudar outros elementos quando um evento ocorre em um elemento específico.

O :hover é um evento que ocorre quando o mouse está sobre um elemento. No CSS para utilizar-lo devemos colocar o nome do elemento e depois o :hover.
Exemplo:

```css
a:hover {
  color: red;
}
```

O :active é um evento que ocorre quando o elemento está sendo clicado. No CSS para utilizar-lo devemos colocar o nome do elemento e depois o :active.

Exemplo:

```css
a:active {
  color: red;
}
```

Agora para fazer com que outros elementos mudem quando um evento ocorre em um elemento específico devemos colocar o elemento que será atingido pelo evento no lado direito do seletor e no lado esquerdo o elemento_que_terá_o_evento:evento.
Exemplo:

```css
li:hover a {
  color: red;
}
```
