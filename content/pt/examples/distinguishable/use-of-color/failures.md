---
weight: 1
title: "Falhas"
date: 2025-04-04
---

## Falha devido a ter uma alternativa textual que não inclui informações transmitidas pelas diferenças de cor na imagem

### Exemplo:

Um gráfico de barras com dados de vendas é fornecido como uma imagem. O gráfico inclui as cifras anuais de vendas para quatro colaboradores no Departamento de Vendas. A alternativa textual para a imagem diz: "O seguinte gráfico de barras exibe as cifras anuais de vendas do Departamento de Vendas. Maria vendeu 3,1 milhões; Fred, 2,6 milhões; Bob, 2,2 milhões; e Andrew, 3,4 milhões. As barras vermelhas indicam vendas abaixo da quota anual." Esta alternativa textual falha ao fornecer as informações transmitidas pela cor vermelha na imagem. A alternativa deve indicar quais pessoas não atingiram a quota de vendas, em vez de confiar na cor.

## Falha devido à criação de links que não são visualmente evidentes sem visão de cores

### Exemplo: Links sem sublinhados e com contraste semelhante ao texto do corpo

<pre aria-label="Exemplo de código em HTML"><code>&lt;head&gt;
  &lt;style&gt;
    p a:link {text-decoration: none}
    p a:visited {text-decoration: none}
    p a:active {text-decoration: none}
    p a:hover {text-decoration: underline; color: red;}
  &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;p&gt;Existem muitos recursos para saber mais sobre a 
     &lt;a href=&quot;chuva-na-espanha.html&quot;&gt;chuva na Espanha&lt;/a&gt;.
  &lt;/p&gt;
&lt;/body&gt;</code></pre>
