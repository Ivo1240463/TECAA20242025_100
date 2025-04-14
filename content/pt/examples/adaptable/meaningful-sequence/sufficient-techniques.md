---
weight: 2
title: "Técnicas Suficientes"
date: 2025-04-04
---

## Ordenando o conteúdo numa sequência significativa

### Exemplo:

Uma página web de uma exposição de museu contém uma barra de navegação com uma longa lista de links. A página também contém uma imagem de uma das obras da exposição, um título para a imagem e uma descrição detalhada da imagem. Os links na barra de navegação formam uma sequência significativa. O título, a imagem e o texto da descrição também formam uma sequência significativa. O CSS é usado para posicionar os elementos na página.

#### Bloco HTML:

<pre aria-label="Exemplo HTML para ordenar o conteúdo numa sequência significativa">
&lt;h1&gt;Minha Página do Museu&lt;/h1&gt;
&lt;ul id=&quot;nav&quot;&gt;
  &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 1&lt;/a&gt;&lt;/li&gt;
  &lt;!-- ... --&gt;
  &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 10&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;
&lt;div id=&quot;description&quot;&gt;
  &lt;h2&gt;Mona Lisa&lt;/h2&gt;
  &lt;div&gt;
    &lt;img src=&quot;img.png&quot; alt=&quot;Mona Lisa&quot;&gt;
  &lt;/div&gt;
  &lt;p&gt;...descrição detalhada da imagem...&lt;/p&gt;
&lt;/div&gt;
</pre>

#### Bloco CSS:

<pre aria-label="Exemplo CSS para estilizar o conteúdo numa sequência significativa">
ul#nav {
  float: left;
  width: 9em;
  list-style-type: none;
  margin: 0;
  padding: 0.5em;
  color: #fff;
  background-color: #063;
}

ul#nav a {
  display: block;
  width: 100%;
  text-decoration: none;
  color: #fff;
  background-color: #063;
}

div#description {
  margin-left: 11em;
}
</pre>

## Fazendo com que a ordem do DOM corresponda à ordem visual

### Exemplo:

Um jornal online colocou uma barra de navegação visualmente no canto superior esquerdo da página, diretamente abaixo do seu logótipo inicial. No código-fonte, os elementos de navegação aparecem depois dos elementos que codificam o logótipo.
