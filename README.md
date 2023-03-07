
> ## Based on [Notation](https://github.com/deathau/Notation-for-Obsidian) by **deathau.**

![](cover.png)


Notion has always been one of my favourite softwares for its advanced features, yet simple and user-friendly design that anyone can use. And **Notation** has long been one of my favourite Obsidian themes of all time (thank you, deathau!). The original Notation is still a bit broken after 1.0, so I thought I'd make a new theme that combined, in my personal opinion, the best elements of Notation with the greatest design features of Notion, all optimized for the latest version of Obsidian. With Notation 2, you can experience the power of cover (banner) images, callouts with custom backgrounds, and more (see: **Special Syntax**)


# Special Syntax

## Callout Colors
Callouts are styled to look like Notion callouts by default, with a tranparent background and a faint outline. You can choose the color of any callout with ease: just add the color you want--`red`, `orange`, `yellow`, `green`, `blue`, `purple`, `pink`, `brown`, or `grey`/`gray`--inside the callout type brackets, separated by a `|`. 

> Example: `>[!quote|blue]`

![](Screenshots/callout.png)

![](Screenshots/blue-callout.png)

## Banner Images
> **Created with the help of:** [efemkay](https://forum.obsidian.md/t/css-how-to-style-the-first-image-in-a-note/52839)


![](Screenshots/cover-img.png)

Display an image as a Notion-esque banner, or cover image, by using the css class `cover-img`. Put the image alt `banner` inside the image you want to display as the banner.

### Example:

```markdown
---
cssClass: cover-img
---

![banner](beach.png)
```

Also supports internal images: `![[beach.png|banner]]`.


### Modifier Alts

Add another alt, `lower` or `higher` to control the positioning of the cover image.

`![banner|higher](beach.png)`

`![banner|lower](beach.png)`


## Text Classes
In Notion, there are three fonts to choose from for each note: Sans, Serif, and Mono. With this theme, you can do the same!

> Note: you can also change the default global font from Style Settings.

### Serif
To use the Serif font in a note, use the css class `serif`.

```markdown
---
cssClass: serif
---
```

### Mono
To use the Monospace font in a note, use the css class `mono`.

```markdown
---
cssClass: mono
---
```

### Sans
To use Sans, the default font in a note, use the css class `sans`.

```markdown
---
cssClass: sans
---
```

## Other Classes

### `small-text`
Make the text in your note smaller.

```markdown
---
cssClass: small-text
---
```

## `wide`
Make your note full-width.

```markdown
---
cssClass: wide
---
```

# Some Other Cool Things
I tried as best as I could to mimic Notion's interface. Tags inside notes are multi-colored, Dataview tables have property icons, the backlinks block has been restyled, frontmatter looks like multi-select properties, inline dataview looks like text properties, Page Gallery plug-in looks the cards view of a database...

You can also use Notation's original color scheme (which I personally prefer over Notion's real colors) by toggling it in Style Settings.

# Credits ⭐

A huuuuge thanks to...

- deathau for the amazing Notation theme!
- efemkay for most of the banner images code - I would never have figured that out on my own!
- subframe7536 for the beautiful Maple theme, which I referenced for the colorful tags
- SIRvb for the ITS theme, which I referenced for the callout colors
- The developers of Obsidian - four months ago I did not know CSS, but because of your app, *now I do*. Thank you so much for this app!


