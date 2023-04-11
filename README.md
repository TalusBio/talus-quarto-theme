# A Talus-branded Quarto presentation theme

This repo defines an Quarto extension to create a Talus-theme revealjs presentation. 

To use in your presentation, first get the theme:

``` sh
quarto add talusbio/talus-quarto-theme
```

Then specify it as a format in your presentation using the YAML header:

``` markdown
---
title: "A Test Presentation"
subtitle: "My subtitle"
author: "Imma Marmot"
date: "2023-04-11"
institute: "Talus Bio"
event: "my event"
format: talusbio-revealjs # <- this is what you need.
---

## My first slide

This one has a dark background

- has bullets
- that are cool
```

See more about quarto presentations here: https://quarto.org/docs/presentations/revealjs/

See more about quarto extensions here: https://quarto.org/docs/extensions/
