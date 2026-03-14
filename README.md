# Quarto UC Davis theme

A UC Davis-branded presentation theme for Quarto Reveal.js. Uses **Atkinson Hyperlegible Next** for text, **Source Code Pro** for code, and the official UC Davis color palette (Aggie Blue and Aggie Gold) on an off-white background.

![](ucdavis-title.png)

## Use

Depending on your use case, here are some [Quarto CLI](https://quarto.org/)
commands to get started.

If you would like to add the **ucdavis** theme to an existing directory:

```bash
quarto install extension hail2thief/quarto-revealjs-ucdavis
```

Alternatively, you can use a
[Quarto template](https://quarto.org/docs/extensions/starter-templates.html)
that bundles the **ucdavis** theme plus a .qmd starter document:

```bash
quarto use template hail2thief/quarto-revealjs-ucdavis
```

Then, in your document YAML header:

```yaml
format: ucdavis-revealjs
```

## Colors

The theme uses the official UC Davis brand colors:

| Color | Hex | Usage |
|---|---|---|
| Aggie Blue | `#022851` | Title, links, buttons |
| Aggie Blue (soft) | `#1B4F72` | h4, list markers |
| Aggie Gold (muted) | `#B3A369` | Subtitles, h3, alerts |
| Aggie Gold (bright) | `#FFBF00` | Available as `$ucdavis-gold` |
| Off-white | `#F5F5F5` | Slide background |

## Acknowledgments

Based on the [clean](https://github.com/grantmcdermott/quarto-revealjs-clean) theme by [Grant McDermott](https://grantmcdermott.com/), which was inspired by Kyle Butts' [LaTeX template](https://raw.githack.com/kylebutts/templates/master/latex-slides/slides.pdf).
