---
weight: 3
title: "Técnicas Suficientes"
date: 2025-04-04
---

## Situação A:
Se uma descrição curta pode cumprir o mesmo propósito e apresentar as mesmas informações que o conteúdo não textual

### Técnica de alternativa de texto curta - Usando aria-label para fornecer rótulos para objetos

#### Exemplo: Distinção de marcos de navegação

O seguinte exemplo mostra como `aria-label` pode ser utilizado para distinguir dois marcos de navegação num documento HTML, onde há mais de dois do mesmo tipo de marco na mesma página, e não existe texto na página que possa ser referenciado como o rótulo.
<pre aria-label="Exemplo de Código em HTML"><code>&lt;div role="navigation" aria-label="Primário"&gt;
  &lt;ul&gt;
    &lt;li&gt;...uma lista de links aqui ...&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
&lt;div role="navigation" aria-label="Secundário"&gt;
  &lt;ul&gt;
    &lt;li&gt;...uma lista de links aqui ...&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
</code></pre>

## Situação B:
Se uma descrição curta não pode cumprir o mesmo propósito e apresentar as mesmas informações que o conteúdo não textual (por exemplo, um gráfico ou diagrama)

### Técnica de alternativa de texto curta - Usando aria-labelledby para fornecer uma alternativa de texto para conteúdo não textual

#### Exemplo: Fornecendo uma descrição curta para um gráfico complexo
Este exemplo mostra como usar o atributo aria-labelledby para fornecer uma descrição curta em texto para um gráfico complexo de padrão de classificação por estrelas; o gráfico é composto por vários elementos de imagem. A alternativa de texto para o gráfico é o rótulo, visível na página abaixo do padrão de estrelas.
<pre aria-label="Exemplo de Código em HTML"><code>&lt;div role="img" aria-labelledby="star-id"&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="emptystar.png" alt=""&gt;
&lt;/div&gt;
&lt;div id="star-id"&gt;4 de 5&lt;/div&gt;
</code></pre>
