---
weight: 1
title: "Falhas"
date: 2025-04-04
---

## Falha devido ao uso de caracteres de espaço em branco para formatar tabelas em conteúdo de texto simples

### Exemplo:

<table aria-label="Tabela com caracteres de espaço em branco">
  <thead>
    <tr>
      <th>Menu</th>
      <th>Café da manhã</th>
      <th>Almoço</th>
      <th>Jantar</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Segunda-feira</td>
      <td>2 ovos fritos<br>bacon<br>torradas</td>
      <td>sopa de tomate<br>hambúrguer<br>anéis de cebola</td>
      <td>salada verde<br>frango frito<br>feijão verde</td>
    </tr>
    <tr>
      <td></td>
      <td>bolacha de aveia</td>
      <td></td>
      <td>puré de batata</td>
    </tr>
    <tr>
      <td>Terça-feira</td>
      <td>Panquecas<br>salsichas<br>sumo de laranja</td>
      <td>sopa de legumes<br>cachorros-quentes<br>salada de batata</td>
      <td>salada Caesar<br>Espaguete com almôndegas<br>pão italiano</td>
    </tr>
    <tr>
      <td></td>
      <td>brownie</td>
      <td></td>
      <td>sorvete</td>
    </tr>
  </tbody>
</table>

## Falha devido ao uso de caracteres de espaço em branco para controlar o espaçamento dentro de uma palavra

### Exemplo: Falha devido à adição de espaço em branco no meio de uma palavra

Este exemplo tem espaços em branco dentro de uma palavra para separar as letras em um título. Leitores de tela podem ler cada letra individualmente, em vez da palavra "Bem-vindo."

<pre aria-label="Exemplo de código mostrando um título com espaços entre as letras">
&lt;h1&gt;B e m  V i n d o&lt;/h1&gt;
</pre>

&nbsp; também pode ser usado para adicionar espaço em branco, produzindo falhas semelhantes:

<pre aria-label="Exemplo de código mostrando um título com espaços não quebráveis entre as letras">
&lt;h1&gt;B&amp;nbsp;E&amp;nbsp;M&amp;nbsp;V&amp;nbsp;I&amp;nbsp;N&amp;nbsp;D&amp;nbsp;O&lt;/h1&gt;
</pre>
