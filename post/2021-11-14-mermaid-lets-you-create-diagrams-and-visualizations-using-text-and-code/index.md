---
title: Mermaid lets you create diagrams and visualizations using text and code.
author: Oleg Baydakov
date: '2021-11-14'
slug: []
categories:
  - javascript
tags:
  - visualization
description: ''
thumbnail: '/post/2021-11-14-mermaid-lets-you-create-diagrams-and-visualizations-using-text-and-code/images/image.png'
---

It is a Javascript based diagramming and charting tool that renders Markdown-inspired text definitions to create and modify diagrams dynamically

[Link](https://mermaid-js.github.io/mermaid/#/)

[mermaid-live-editor](https://github.com/mermaid-js/mermaid-live-editor)

[Python Integration with mermaid-js](https://mermaid-js.github.io/mermaid/#/Tutorials?id=python-integration-with-mermaid-js)

Example:

sequenceDiagram

    participant Alice

    participant Bob

    Alice->>John: Hello John, how are you?

    loop Healthcheck

        John->>John: Fight against hypochondria
    end

    Note right of John: Rational thoughts <br/>prevail!

    John-->>Alice: Great!

    John->>Bob: How about you?

    Bob-->>John: Jolly good!


![](images/sequence.png)