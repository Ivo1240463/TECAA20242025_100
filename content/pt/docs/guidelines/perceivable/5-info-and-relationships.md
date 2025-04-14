---
title: Informação e Relações
linkTitle: 5- Informação e Relações
---

## Informação e Relações

Ao conceber conteúdo web, não basta focar apenas na apresentação visual, a estrutura e o significado também devem ser claros para as tecnologias de apoio. Isto garante que utilizadores que dependem de leitores de ecrã ou outras ferramentas possam compreender como a informação está organizada e como os diferentes elementos se relacionam entre si.

Esta diretriz apoia utilizadores com deficiências visuais, cognitivas e de aprendizagem, tornando o conteúdo mais previsível e fácil de navegar.

## Regra Geral

A informação, a estrutura e as relações transmitidas através da apresentação visual devem também ser:

- Determinadas programaticamente  
- Disponíveis em formato de texto.

Isto permite que utilizadores com deficiência percebam e interajam com o conteúdo de forma significativa e eficiente.

## Situações Específicas

### Títulos e Rótulos
Utilize corretamente as tags HTML (`<h1>` a `<h6>`) para indicar títulos. Isto ajuda os utilizadores de leitores de ecrã a compreender a hierarquia e organização do conteúdo. Evite usar apenas estilo visual (como texto em negrito ou fontes grandes) para indicar títulos.

### Listas e Agrupamentos
Certifique-se de que as listas são marcadas com tags HTML semânticas como `<ul>`, `<ol>` e `<li>`. Agrupe campos de formulário relacionados usando `<fieldset>` e `<legend>` para transmitir relações.

### Tabelas
Use marcação apropriada para tabelas (`<table>`, `<thead>`, `<tbody>`, `<th>` e `<td>`) para indicar relações entre dados. Forneça cabeçalhos de tabela para explicar como os dados estão organizados.

## Exemplos
{{< cards >}}
  {{< card url="../../../../examples/adaptable/info-relationships" title="Informação e Relações Exemplos" icon="chevron-right" >}}
{{< /cards >}}