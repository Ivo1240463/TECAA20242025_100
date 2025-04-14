---
weight: 3
title: "Sufficient Techniques"
date: 2025-04-04
---

## Providing a second, user-selectable, audio track that includes audio descriptions

### Examples:

- A travelogue of the northeast has additional audio description added during the gaps in the dialogue to let listeners who are blind know what the person is talking about at any point in time.
- A video shows a woodpecker carving a nest in a tree. A button within the content allows users to turn the audio description track on or off.

## Using a static text alternative to describe a talking head video

### Example: A video of a CEO speaking to shareholders

A CEO is speaking to shareholders from their office. The video has a title page at the beginning of the video giving the date. When the speaker begins, there is a strip of text at the bottom of the video saying "Jane Doe, President of XYZ Cooperation". At the end of the video are title credits that say "produced by the Honest TV Productions Ltd."

As an alternative, there is a paragraph below the video which is associated with the video file using `aria-describedby` which says: "July 22, 2011, Jane Doe, President of XYZ cooperation, speaking from her office. Video produced by the Honest TV Productions Ltd."
