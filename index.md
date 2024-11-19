---
title: "Presentation Template"
subtitle: "Create beautiful interactive slide decks with Reveal.js"
author: "Your Name"
date: "November 19, 2024"
format:
  revealjs:
    center: true
    center-title-slide: true
    slide-number: true
    chalkboard: 
      buttons: false
    preview-links: auto
    logo: images/logo_no_text.png
    footer: "[developmentseed.org](https://developmentseed.org)"
    theme: white # try black for dark theme
    css: styles.css    
    navigation-mode: vertical
    controls-layout: bottom-right
    controls-tutorial: true
    execute:
      echo: true
      eval: true
      warning: false
      cache: true
title-slide-attributes:
    data-background-image: images/devseed_background.png
---

# First slide

- you can make pretty slides in a markdown document!
- check out the [Quarto reveal.js guide](https://quarto.org/docs/presentations/revealjs/) for tips

# Pretty Code {auto-animate="true"}

- Over 20 syntax highlighting themes available
- Default theme optimized for accessibility

## Python

```python
import rasterio

```


# iframes

- fill entire slide with `background-iframe`
- add an iframe in a slide

## {background-interactive=true background-iframe="https://landsatlook.usgs.gov/explore?date=2024-10-17%7C2024-11-14&sat=LANDSAT_9%7CLANDSAT_8"}

::: footer
<https://landsatlook.usgs.gov/explore>
:::


## Explore STAC Browser {.hide-title}

- add slide content and an iframe

::: {.r-stretch}
<iframe 
  src="https://radiantearth.github.io/stac-browser/#/?.language=en" 
  width="100%"
  height="100%"
  style="border: none;"
  allowFullScreen>
</iframe>
:::

- and a custom footer

::: footer
<https://radiantearth.github.io/stac-browser/#/?.language=en>
:::

# images

##

![](https://stacspec.org/public/images-original/STAC-01.png){.r-stretch}


