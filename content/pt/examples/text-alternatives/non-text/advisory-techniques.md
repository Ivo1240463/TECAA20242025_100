---
weight: 2
title: "Técnicas Consultivas"
date: 2025-04-04
---

## Usando as regras de margem e preenchimento CSS em vez de imagens de espaçamento para o design de layout

### Exemplo: Distinguindo marcos de navegação

O seguinte exemplo consiste em duas partes: o código CSS, que especifica uma margem em todos os lados da tabela, e o preenchimento para as células da tabela; e o código HTML para a tabela, que não contém imagens de espaçamento e não está aninhada dentro de outra tabela.

### Bloco CSS:

<pre aria-label="Exemplo de Código em CSS"><code>table { margin: .5em; border-collapse: collapse; } 
td, th { padding: .4em; border: 1px solid #000; }
</code></pre>
### Bloco HTML:
<pre aria-label="Exemplo de Código em HTML"><code>&lt;table&gt;
  &lt;caption&gt;Livros na categoria 'Desenvolvimento Web'&lt;/caption&gt;
  &lt;thead&gt;
    &lt;tr&gt;
      &lt;th&gt;Título&lt;/th&gt;
      &lt;th&gt;Autor&lt;/th&gt;
      &lt;th&gt;Data&lt;/th&gt;
    &lt;/tr&gt;
  &lt;/thead&gt;
  &lt;tbody&gt;
    &lt;tr&gt;
      &lt;td&gt;Como Pensar Corretamente Sobre os Padrões Web&lt;/td&gt;
      &lt;td&gt;Andrew Stanovich&lt;/td&gt;
      &lt;td&gt;1 de Abril de 2007&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/tbody&gt;
&lt;/table&gt;
</code></pre>
