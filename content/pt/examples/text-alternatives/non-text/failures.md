---
weight: 1
title: "Falhas"
date: 2025-04-04
---

## Falha devido ao uso de CSS para incluir imagens que transmitem informações importantes

### Exemplo:

No seguinte exemplo, parte do conteúdo é contida numa imagem que é apresentada apenas pelo CSS. Nesta situação, a imagem `TopRate.png` é uma imagem de 180 por 200 pixels que contém o texto: "19,3% APR Taxa Variável Típica."

### Bloco CSS
<pre aria-label="Exemplo de Código em CSS"><code>p#bestinterest {
   padding-left: 200px;
   background: transparent url(/images/TopRate.png) no-repeat top left;
}
</code></pre>
### Quando usada neste Bloco HTML
<pre aria-label="Exemplo de Código em HTML"><code>&lt;p id="bestinterest"&gt;Onde mais você encontraria uma taxa de juros melhor?&lt;/p&gt;
</code></pre>

## Falha devido à alternativa de texto que não inclui informações transmitidas pelas diferenças de cor na imagem

### Exemplo:
Um gráfico de barras de dados de vendas é fornecido como uma imagem. O gráfico inclui os números de vendas anuais para quatro funcionários do Departamento de Vendas. A alternativa de texto para a imagem diz: "O seguinte gráfico de barras exibe os números de vendas anuais para o Departamento de Vendas. Mary vendeu 3,1 milhões; Fred, 2,6 milhões; Bob, 2,2 milhões; e Andrew, 3,4 milhões. As barras vermelhas indicam vendas abaixo da cota anual". Esta alternativa de texto não fornece as informações que são transmitidas pela cor vermelha na imagem. A alternativa deveria indicar quais pessoas não cumpriram a cota de vendas, em vez de depender da cor.
