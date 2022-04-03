# Krafty

A theme which makes your Typora feel like you’re writing on a Kraft notebook.

---

## Images

What kind of Kraft notebook isn’t plastered all over with instant photos? Not this one, that’s for sure. Images in Krafty are styled with a Polaroid-esque look; a white border, space for labels at the bottom, subtly off-kilter… For an example of how images look, check out the background of this page courtesy of [Jill Burrow](https://www.pexels.com/@jill-burrow) via [Pexels ](https://www.pexels.com/) (thank you!):

![Background Image](../typora/krafty/krafty-bg.jpeg)

## Code

Code blocks have a white background to stand out against the off-white page, as well as plenty of space around:

```css
/* Here's the code, if you're curious! */

pre, #write .CodeMirror {
  background-color: white;
  font-family: var(--mono);
  padding: 5mm;
  margin: 5mm 0;
  border: none !important;
}
```

In code view, you also have a line under each line of text. Super helpful to see how many line breaks you’ve used!

## Tables

Tables have headers formatted like page headers and cells with a thick white border on the bottom.

| Part of the table | Style                                  | Font        |
| ----------------- | -------------------------------------- | ----------- |
| Header            | White background                       | Roboto Slab |
| Cell              | No background, but white bottom border | Outfit      |



## Fonts

Krafty uses free fonts from [Google Fonts](fonts.google.com), getting them direct from their website, so you don’t need to have them installed! If you’re interested, the three font families used are:

**[Outfit](fonts.google.com/specimen/Outfit)** (for most text)

![Outfit font sample (via Fontke)](https://statics.fontke.com/image/image/2204176/360x270.png)

**[Roboto Slab](fonts.google.com/specimen/Roboto+Slab)** (for headings)

![Roboto Slab font sample (via Fontke)](https://statics.fontke.com/image/image/851153/360x270.png)

**[JetBrains Mono](fonts.google.com/specimen/JetBrains+Mono)** (for code)

![JetBrains Mono font sample (via Fontke)](https://statics.fontke.com/image/image/2052943/360x270.png)

## So… This is in Typora?

Yep! No extra HTML added, just the standard Typora parsed [MarkDown](https://www.markdownguide.org/basic-syntax/) output. The fancy graphics are all SVG backgrounds applied to the `:before` and `:after` tags of the main writing area. 