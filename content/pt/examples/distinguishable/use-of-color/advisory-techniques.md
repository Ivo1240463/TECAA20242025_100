---
weight: 2
title: "Técnicas Consultivas"
date: 2025-04-04
---

## Usando CSS para alterar a apresentação de um componente da interface do utilizador quando recebe foco

### Exemplo: Elementos de link

Neste exemplo, indicadores de foco por mouse e teclado foram aplicados aos elementos de link. O CSS foi utilizado para aplicar uma cor de fundo quando os elementos de link recebem foco.

Aqui está o conteúdo a ser exibido:
<pre aria-label="Exemplo de código em HTML"><code>&lt;nav id=&quot;main-nav&quot;&gt;
  &lt;ul&gt;
    &lt;li&gt;Início&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/servicos&quot;&gt;Serviços&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/projetos&quot;&gt;Projetos&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/demos&quot;&gt;Demonstrações&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/sobre-nos&quot;&gt;Sobre nós&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/contactar-nos&quot;&gt;Contacte-nos&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/links&quot;&gt;Links&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/nav&gt;</code></pre>
Aqui está o CSS que altera a cor de fundo para os elementos acima quando recebem foco por mouse ou teclado:
<pre aria-label="Exemplo de código em CSS"><code>#main-nav a:hover, #main-nav a:active, #main-nav a:focus-visible {
  background-color: #DCFFFF;
  color: #000066;
}</code></pre>
