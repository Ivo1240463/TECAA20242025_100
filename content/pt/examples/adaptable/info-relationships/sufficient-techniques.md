---
weight: 3
title: "Técnicas Suficientes"
date: 2025-04-04
---

## Situação A: 
A tecnologia fornece estrutura semântica para tornar as informações e relações transmitidas através da apresentação programaticamente determináveis.

### Usando marcos ARIA para identificar regiões de uma página
#### Exemplo: Marcos simples
O seguinte exemplo mostra como marcos podem ser adicionados a um documento HTML:

<pre aria-label="Exemplo de código mostrando marcos ARIA simples para identificar regiões">
&lt;div role=&quot;banner&quot;&gt;logotipo e nome do site, etc. aqui&lt;/div&gt;
&lt;div role=&quot;search&quot;&gt;funcionalidade de pesquisa aqui&lt;/div&gt;
&lt;div role=&quot;navigation&quot;&gt;uma lista de links de navegação aqui&lt;/div&gt;
&lt;div role=&quot;form&quot;&gt;um formulário de inscrição aqui&lt;/div&gt;
&lt;div role=&quot;main&quot;&gt;o conteúdo principal da página aqui&lt;/div&gt;
&lt;div role=&quot;region&quot;&gt;uma promoção de patrocinador aqui&lt;/div&gt;
&lt;div role=&quot;complementary&quot;&gt;conteúdo da barra lateral aqui&lt;/div&gt;
&lt;div role=&quot;contentinfo&quot;&gt;detalhes de contato do site, informações de copyright, etc. aqui&lt;/div&gt;
</pre>

## Situação B: 
A tecnologia em uso NÃO fornece a estrutura semântica para tornar as informações e relações transmitidas através da apresentação programaticamente determináveis.

### Usando texto para transmitir informações que são transmitidas por variações na apresentação do texto
#### Exemplo: Indicando novo conteúdo com negrito e um indicador de texto
O seguinte exemplo mostra uma lista de normas de acessibilidade. A WCAG 2.2 é nova, portanto, é indicada em negrito. Para evitar transmitir informações exclusivamente pela apresentação, a palavra "(novo)" é incluída após ela também.

<pre aria-label="Exemplo de código mostrando normas de acessibilidade com negrito e indicador de texto para novo conteúdo">
&lt;h2&gt;Diretrizes de Acessibilidade na Web&lt;/h2&gt;
&lt;ul&gt;
  &lt;li&gt;&lt;strong&gt;WCAG 2.2 (Novo)&lt;/strong&gt;&lt;/li&gt;
  &lt;li&gt;WCAG 2.1&lt;/li&gt;
  &lt;li&gt;WCAG 2.0&lt;/li&gt;
  &lt;li&gt;Seção 508&lt;/li&gt;
  &lt;li&gt;JIS X 8341-3&lt;/li&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ul&gt;
</pre>
