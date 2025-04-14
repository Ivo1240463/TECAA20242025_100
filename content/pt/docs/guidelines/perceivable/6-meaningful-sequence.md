---
title: Sequência Significativa
linkTitle: 6- Sequência Significativa
---

## Sequência Significativa

Em alguns conteúdos web, a ordem em que a informação é apresentada é essencial para compreender o seu significado. Isto é especialmente importante para utilizadores que dependem de leitores de ecrã, que experienciam o conteúdo de forma linear.

Se o layout visual de uma página sugerir uma sequência de leitura específica, essa mesma sequência deve ser determinável programaticamente, para que possa ser transmitida de forma precisa pelas tecnologias de apoio.

## Regra Geral

Quando a sequência de conteúdo afeta o seu significado, a ordem correta de leitura deve ser:

- Determinada programaticamente, para que possa ser acedida por leitores de ecrã e outras ferramentas de apoio.

Isto garante que os utilizadores possam percecionar o conteúdo na ordem pretendida, mantendo a clareza e a compreensão.

## Situações Específicas

### Layouts em Múltiplas Colunas
Se o conteúdo for apresentado em múltiplas colunas (texto lado a lado), certifique-se de que a ordem do código HTML reflete a sequência de leitura pretendida. Não dependa exclusivamente do CSS para layout se este alterar a ordem lógica.

### Instruções Passo a Passo
Para etapas ou instruções ordenadas, utilize elementos HTML semânticos como `<ol>` para preservar a sequência correta. Evite colocar etapas fora de ordem visualmente ou no código.

### Tabelas
Certifique-se de que a ordem de leitura dentro das tabelas corresponde ao fluxo lógico dos dados, da esquerda para a direita, de cima para baixo, a menos que uma ordem diferente seja intencional e clara.

### Leitores de Ecrã e Ordem do Código
Use com cuidado marcos ARIA e elementos HTML para que os leitores de ecrã sigam o caminho correto de leitura. Evite colocar conteúdo chave fora de sequência no DOM, mesmo que este apareça no local certo visualmente.

### Layouts Responsivos
Em ecrãs menores ou quando o conteúdo se reorganiza, certifique-se de que a ordem de leitura ainda faz sentido e reflete a sequência pretendida.

## Exemplos
{{< cards >}}
  {{< card url="../../../../examples/adaptable/meaningful-sequence" title="Sequência Significativa Exemplos" icon="chevron-right" >}}
{{< /cards >}}