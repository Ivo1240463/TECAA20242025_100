---
weight: 2
title: "Advisory Techniques"
date: 2025-04-04
---


 ## Using the track element to provide audio descriptions

### Example: Audio description in multiple languages

A video element for a video with both an English and French language source element, and with an English and a French audio description track using the WebVTT file format.
 <pre aria-label = "Code Example in HTML"><code>&lt;video poster=&quot;myvideo.png&quot; controls&gt;
  &lt;source src=&quot;myvideo.mp4&quot; srclang=&quot;en&quot; type=&quot;video/mp4&quot;&gt;
  &lt;source src=&quot;myvideo.webm&quot; srclang=&quot;fr&quot; type=&quot;video/webm&quot;&gt;
  &lt;track kind=&quot;descriptions&quot; label=&quot;English&quot; src=&quot;myvideo-en.vtt&quot; srclang=&quot;en&quot;&gt;
  &lt;track kind=&quot;descriptions&quot; label=&quot;Français&quot; src=&quot;myvideo-fr.vtt&quot; srclang=&quot;fr&quot;&gt;
&lt;/video&gt;
</code></pre>
