---
title: Amatl
subtitle: server
dateupdate: 01/04/2024
version: 1.1
author: https://github.com/Bornholm
---
:include{url="./misc/amatl/pagegarde.md"}

# Amatl

This extension is based on [Amatl](https://github.com/Bornholm/amatl), a binary tool that allows you to convert your Markdown files into HTML and PDF formats.

Transform your [CommonMark](https://commonmark.org/) (also known as [Markdown](https://en.wikipedia.org/wiki/Markdown)) files into full-fledged documents from the command line.

> **Why the name `amatl`?**  
> Amate (Spanish: amate `[aˈmate]`, from Nahuatl languages: āmatl `[ˈaːmat͡ɬ]`) is a type of bark paper that has been manufactured in Mexico since pre-Columbian times. It was primarily used to create codices.  
> **Source:** [Wikipedia](https://en.wikipedia.org/wiki/Amate)

### ✨ Features

- Create documents from local or remote resources via URL resolving.
- Integrate [MermaidJS](https://mermaid.js.org/) diagrams and code blocks with syntax highlighting.
- Use [custom directives](https://github.com/Bornholm/amatl/tree/master/doc/directives/README.md) to include other documents or generate tables of contents.
- Use [pre-defined or custom layouts](https://github.com/Bornholm/amatl/tree/master/doc/layouts/README.md) to transform your content into presentations, reports, etc.
- Use [Go templating](https://github.com/Bornholm/amatl/tree/master/doc/templating/README.md) to inject dynamic data into your document.

### 🚀 How to Use

> **⚠ Caution**  
> This project is in its early stages and subject to rapid evolution. Expect frequent changes and potential instability.

1. Download [the latest release](https://github.com/Bornholm/amatl/releases/latest) of `amatl`.
2. In your terminal, start transforming your documents into HTML:

```shell
amatl render html my-doc.md
```

See [`doc`](https://github.com/Bornholm/amatl/tree/master/doc/README.md) for more information.


