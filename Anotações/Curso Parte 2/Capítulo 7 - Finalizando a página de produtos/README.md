# Neste capítulo vi sobre o footer, colocar uma imagem de background em um elemento e o unicode

O footer é uma tag semântica que serve para colocar informações de rodapé, no nosso projeto colocamos uma imagem de background nesse elemento, e para fazer isso é da seguinte forma:

```css
footer {
  background-image: url(../img/footer-background.png);
}
```

Também colocamos um texto de copyright e tivemos que colocar um &copy; para que o texto ficasse com o símbolo de copyright, para isso usamos o unicode, que é um código que representa um caractere, e para colocar esse caractere usamos a seguinte forma:

```html
<p>&copy;</p>
```

Para saber mais sobre unicode acesse: https://unicode-table.com/pt/
