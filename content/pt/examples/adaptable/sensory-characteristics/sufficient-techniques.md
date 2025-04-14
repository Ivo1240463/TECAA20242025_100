---
weight: 2
title: "Técnicas Suficientes"
date: 2025-04-04
---

## Fornecer identificação textual de elementos que, de outra forma, dependeriam apenas de informação sensorial para serem compreendidos

### Exemplo 1: Botão referido pela forma e pelo nome acessível
Um botão redondo é disponibilizado num formulário para submeter o formulário e avançar para o passo seguinte. O botão tem a etiqueta de texto "go". As instruções indicam: "Para submeter o formulário, prima o botão redondo com a etiqueta 'go'." Isto inclui tanto a forma como informação textual para localizar o botão.

### Exemplo 2: Uma secção de ligações de navegação referida pela localização e pelo título
As instruções de uma página web que disponibiliza formação online indicam: "Use a lista de ligações à direita com o título 'Lista de Aulas' para navegar até ao curso online desejado." Esta descrição fornece pistas sobre a localização, bem como pistas textuais para ajudar a encontrar a lista correta de ligações.

### Exemplo 3: Botão referido pela posição e pelo nome acessível
O layout seguinte coloca um botão no canto inferior direito e indica-o pela sua posição. A indicação da etiqueta de texto clarifica qual o botão a utilizar para utilizadores para os quais a posição não é significativa.

#### Bloco HTML:
<pre aria-label="Exemplo de codigo de um form em HTML"><code>&lt;form class=&quot;wrapper&quot;&gt;
  &lt;h1&gt;Sign up to our mailing list&lt;/h1&gt;
    &lt;div role=&quot;note&quot;&gt;
      Complete the form and then press the lower-right (&lt;i&gt;sign up&lt;/i&gt;) button.
    &lt;/div&gt;
  &lt;div class=&quot;form-group&quot;&gt;
    &lt;label for=&quot;full-name&quot;&gt;Your name&lt;/label&gt;
    &lt;input autocomplete=&quot;name&quot; id=&quot;full-name&quot; type=&quot;text&quot;&gt;
  &lt;/div&gt;
  &lt;div class=&quot;form-group&quot;&gt;
    &lt;label for=&quot;email&quot;&gt;Your email address&lt;/label&gt;
    &lt;input autocomplete=&quot;email&quot; id=&quot;email&quot; type=&quot;text&quot;&gt;
  &lt;/div&gt;
  &lt;button type=&quot;reset&quot;&gt;Cancel&lt;/button&gt;
  &lt;button type=&quot;submit&quot;&gt;Sign up&lt;/button&gt;
&lt;/form&gt;</code></pre>
#### Bloco CSS:
<pre aria-label="Exemplo de codigo CSS"><code>
.wrapper{
  border: 1px solid #aeaeae;
  display: grid;
  gap: 1rem;
  grid-template-columns: 1fr 1fr;
  padding: 1rem;
  width: 50vw;
}

label{
  display: block;
}

input, button{
  font: inherit;
}

h1, [role="note"]{
  grid-column: 1 / -1;
}

.form-group{
  grid-column: 1;
}

input{
  width: 100%;
}

button[type="reset"]{
  grid-column: 1;
}

button[type="submit"]{
  grid-column: 2;
}
</code></pre>