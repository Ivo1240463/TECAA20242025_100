---
weight: 2
title: "Técnicas Consultivas"
date: 2025-04-04
---

## Usando CSS para controlar a apresentação visual do texto

### Exemplo: Usando a propriedade CSS font-family para controlar a família da fonte do texto

**O Componente HTML:**
<pre aria-label="Exemplo de código demonstrando como usar a propriedade font-family no CSS para definir a fonte do texto.">
<code>&lt;p&gt;O método JavaScript para converter uma string para maiúsculas é &lt;code&gt;toUpperCase()&lt;/code&gt;.&lt;/p&gt;</code>
</pre>

**O Componente CSS:**
<pre aria-label="Exemplo de código mostrando como aplicar font-family no CSS.">
<code>&lt;code&gt; { font-family:&quot;Courier New&quot;, Courier, monospace }&lt;/code&gt;</code>
</pre>

### Usando a propriedade aria-describedby para fornecer um rótulo descritivo para controles de interface do usuário

**Exemplo: Usando aria-describedby para associar instruções com campos de formulário**

Campo de formulário de exemplo usando `aria-describedby` para associar instruções com campos de formulário, enquanto há um rótulo de formulário.

<pre aria-label="Exemplo de código demonstrando o uso de aria-describedby para associar instruções a um campo de formulário.">
<code>&lt;form&gt;
  &lt;label for=&quot;fname&quot;&gt;Nome&lt;/label&gt;
  &lt;input aria-describedby=&quot;int2&quot; autocomplete=&quot;given-name&quot; id=&quot;fname&quot; type=&quot;text&quot;&gt;
  &lt;p id=&quot;int2&quot;&gt;Seu primeiro nome é às vezes chamado de &quot;nome dado&quot;.&lt;/p&gt;
&lt;/form&gt;</code>
</pre>
