---
title: Controlo de Áudio
linkTitle: 9- Controlo de Áudio
---

## Controlo de Áudio

Quando o áudio é reproduzido automaticamente numa página web, é essencial que os utilizadores possam controlá-lo. Isto é particularmente importante se o áudio for reproduzido durante mais de 3 segundos. Os utilizadores devem poder pausar, parar ou ajustar o volume independentemente do nível de volume geral do sistema, garantindo uma experiência de navegação mais confortável, especialmente para utilizadores com dificuldades auditivas ou para aqueles que necessitam de um ambiente mais silencioso.

## Regra Geral

Se qualquer áudio numa página web for reproduzido automaticamente por mais de 3 segundos, deve estar disponível um dos seguintes mecanismos:

- Um mecanismo para pausar ou parar o áudio
- Um mecanismo para controlar o volume do áudio independentemente do nível de volume geral do sistema.

Isto garante que os utilizadores não sejam forçados a ouvir sons indesejados ou intrusivos sem a capacidade de os ajustar ou silenciar.

## Situações Específicas

### Áudio com Reprodução Automática
Se o áudio começar a ser reproduzido automaticamente quando uma página é carregada, certifique-se de que os utilizadores podem pausar ou parar o áudio dentro de 3 segundos. Forneça controlos claros para parar ou silenciar o som.

### Controlo de Volume
Se o áudio não puder ser pausado ou parado, forneça uma opção para controlar o volume independentemente do volume geral do sistema. Isto é especialmente importante para áudio em reprodutores de mídia ou conteúdo incorporado, como podcasts, vídeos ou sons de fundo.

### Conteúdo Longo
Para conteúdo mais longo, como podcasts ou música de fundo, assegure-se de que os utilizadores têm fácil acesso aos controlos de áudio. Considere adicionar botões para reproduzir/parar, pausar e ajustar o volume.

### Sons de Notificação
Para notificações ou alertas que toquem áudio automaticamente, forneça um método para os utilizadores desligarem ou ajustarem o volume desses sons.

## Exemplos
{{< cards >}}
  {{< card url="../../../../examples/distinguishable/audio-control" title="Controlo de Áudio Exemplos" icon="chevron-right" >}}
{{< /cards >}}