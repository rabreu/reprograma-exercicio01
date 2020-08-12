# reprograma-exercicio01

## HTML e CSS

### HTML

![HTML](https://image.flaticon.com/icons/png/512/29/29515.png | width=100)

HTML (Linguagem de Marcação de HiperTexto) é o bloco de construção mais básico da web. Define o significado e a estrutura do conteúdo da web.

O HTML usa "Marcação" para anotar texto, imagem e outros conteúdos para exibição em um navegador da Web.

Um elemento HTML é separado de outro texto em um documento por "tags", que consistem no nome do elemento entre "<" e ">". O nome de um elemento dentro de uma tag é insensível a maiúsculas e minúsculas. Isto é, pode ser escrito em maiúsculas, minúsculas ou um mistura. Por exemplo, a tag <title> pode ser escrita como <Title>, <TITLE> ou de qualquer outra forma.

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

Fonte: https://developer.mozilla.org/pt-BR/docs/Web/HTML

### CSS

![CSS](https://image.flaticon.com/icons/png/512/29/29088.png | width=100)

CSS (Cascading Style Sheets) é uma linguagem declarativa que controla a apresentação visual de páginas web em um navegador. O navegador aplica as declarações de estilo CSS aos elementos selecionados para exibi-los apropriadamente. Uma declaração de estilo contem as propriedades e seus valores, que determinam a aparência de uma página web.

CSS é uma das três principais tecnologias Web, junto com HTML e JavaScript. CSS normalmente estiliza Elementos HTML, mas também pode ser usada com outras linguagens de marcação como SVG ou XML.

Uma regra CSS é um conjunto de propriedades associados a um seletor. Aqui está um exemplo que faz com que todos os parágrafos HTML fiquem amarelos num fundo preto:

```
/* O seletor "p" indica que todos os paragrafos no documento serão afetados por essa regra */
p {
  /* A propriedade "color" define a cor do texto, neste caso amarelo. */
  color: yellow;

  /* A propriedade "background-color" define a cor ao fundo, neste caso preto. */
  background-color: black
}
```
Fonte: https://developer.mozilla.org/pt-BR/docs/Glossario/CSS
