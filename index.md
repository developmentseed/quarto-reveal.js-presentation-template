---
title: "Presentation Template"
subtitle: "Create beautiful interactive slide decks with Reveal.js"
format:
  revealjs:
    center: false
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


# LandsatLook

- STAC-powered Landsat browser

## {background-interactive=true background-iframe="https://landsatlook.usgs.gov/explore?date=2024-10-17%7C2024-11-14&sat=LANDSAT_9%7CLANDSAT_8"}

::: footer
<https://landsatlook.usgs.gov/explore>
:::


# images

##

![](https://stacspec.org/public/images-original/STAC-01.png){.r-stretch}


