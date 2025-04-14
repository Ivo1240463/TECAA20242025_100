---
weight: 1
title: "Falhas"
date: 2025-04-04
---

## Falha devido ao uso de mudanças na apresentação do texto para transmitir informações sem utilizar a marcação ou o texto apropriado

### Exemplo: Usando CSS para estilizar o elemento p para se parecer com um título

O autor pretendia criar um título, mas não queria a aparência do título HTML padrão. Então, ele usou CSS para estilizar o elemento `P` para se parecer com um título e chamou-o de título. Mas ele falhou ao não usar o elemento de título HTML apropriado. Portanto, a Tecnologia Assistiva não conseguiu distinguir isso como um título.

<pre aria-label="Exemplo de código mostrando como o CSS estiliza um parágrafo para parecer com um título">
&lt;style&gt;
.heading1{
  font-family: Times, serif;
  font-size:200%;
  font-weight:bold;
}
&lt;/style&gt;

&lt;p class=&quot;heading1&quot;&gt;Introdução&lt;/p&gt;
&lt;p&gt;Esta introdução fornece informações detalhadas sobre como usar isto ...&lt;/p&gt;
</pre>

## Falha devido ao uso de marcação estrutural de forma que não representa relações no conteúdo

### Exemplo: Um título usado apenas para efeito visual

Neste exemplo, um elemento de título é usado para exibir um endereço em uma fonte grande e em negrito. No entanto, o endereço não identifica uma nova seção do documento, portanto, não deve ser marcado como um título.

<pre aria-label="Exemplo de código mostrando um título usado para efeito visual para exibir um endereço">
&lt;p&gt;Interessado em aprender mais? Escreva-nos para&lt;/p&gt; 
&lt;h4&gt;3333 Third Avenue, Suite 300 · New York City&lt;/h4&gt;
&lt;p&gt;E nós enviaremos o pacote informativo completo absolutamente grátis!&lt;/p&gt;
</pre>
