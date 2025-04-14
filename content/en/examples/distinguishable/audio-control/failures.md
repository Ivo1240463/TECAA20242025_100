---
weight: 1
title: "Failures"
date: 2025-04-04
---


## Failure due to playing a sound longer than 3 seconds where there is no mechanism to turn it off

### Examples:
- A site that plays continuous background music
- A site with a narrator that lasts more than 3 seconds before stopping, and there is no mechanism to stop it.

## Failure for absence of a way to pause or stop an HTML5 media element that autoplays

### Example: An auto-playing audio track

In this example, the advertising video contains an audio track. The video will play continuously because of the loop attribute, and the video will start automatically because of the autoplay attribute and because there does not appear to be any controls to allow the user to stop the video.

<pre aria-label="Code Example in HTML"><code>&lt;video src=&quot;ads.cgi?kind=video&quot; autoplay loop&gt;&lt;/video&gt;</code></pre>
