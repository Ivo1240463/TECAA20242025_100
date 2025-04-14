---
weight: 2
title: "Técnicas Consultivas"
date: 2025-04-04
---

## Usando o elemento track para fornecer descrições em áudio

### Exemplo: Descrição em áudio em múltiplas línguas

Um elemento de vídeo para um vídeo com ambos os elementos de origem em inglês e francês, e com uma faixa de descrição em áudio em inglês e francês utilizando o formato de arquivo WebVTT.

<pre aria-label="Exemplo de Código em HTML"><code>&lt;video poster=&quot;myvideo.png&quot; controls&gt;
  &lt;source src=&quot;myvideo.mp4&quot; srclang=&quot;en&quot; type=&quot;video/mp4&quot;&gt;
  &lt;source src=&quot;myvideo.webm&quot; srclang=&quot;fr&quot; type=&quot;video/webm&quot;&gt;
  &lt;track kind=&quot;descriptions&quot; label=&quot;Inglês&quot; src=&quot;myvideo-en.vtt&quot; srclang=&quot;en&quot;&gt;
  &lt;track kind=&quot;descriptions&quot; label=&quot;Francês&quot; src=&quot;myvideo-fr.vtt&quot; srclang=&quot;fr&quot;&gt;
&lt;/video&gt;
</code></pre>