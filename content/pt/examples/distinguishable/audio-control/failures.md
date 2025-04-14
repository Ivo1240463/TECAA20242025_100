---
weight: 1
title: "Falhas"
date: 2025-04-04
---

## Falha devido à reprodução de um som por mais de 3 segundos sem existir um mecanismo para o desligar

### Exemplos:
- Um site que reproduz música de fundo contínua.
- Um site com um narrador que dura mais de 3 segundos antes de parar, e não existe um mecanismo para o parar.

## Falha pela ausência de uma forma de pausar ou parar um elemento de mídia HTML5 que é reproduzido automaticamente

### Exemplo: Uma faixa de áudio que toca automaticamente

Neste exemplo, o vídeo publicitário contém uma faixa de áudio. O vídeo será reproduzido continuamente devido ao atributo loop, e o vídeo começará automaticamente devido ao atributo autoplay, não parecendo haver controles para permitir ao usuário parar o vídeo.

<pre aria-label="Exemplo de código em HTML"><code>&lt;video src=&quot;ads.cgi?kind=video&quot; autoplay loop&gt;&lt;/video&gt;</code></pre>
