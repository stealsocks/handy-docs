---
title: Snippets
---

These are pieces of code that I find myself using most often. If you can think of something that belongs on here, [let me know](https://twitter.com/joodalooped.com), or send a pull request.

### Importing a font

You need to change the 'font-weight' and 'font-style' fields to to match the weight of the imported font, and whether it's italic or normal.

```css
@font-face {
    font-family: 'SourceSans';
    font-style: normal;
    src: url('/fonts/SourceSans.ttf');
    font-display: swap;
    font-weight: 400;  
}
```

### Dotted background

```css
.dotted-bg {
  background-image: conic-gradient(
    at 92% 8%,
    #202128 90deg,
    transparent 0 225deg,
    transparent 0
  );
  background-size: 16px 16px;
}
```
[Source](https://twitter.com/brotzky_/status/1749506883663327557)

### Gradient border

```css
.gradient-border {
  background: linear-gradient(white, white) padding-box, linear-gradient(
        to right,
        blue,
        red
      ) border-box;
  border: 1px solid transparent;
}
```
[Source](https://twitter.com/brotzky_/status/1750568966555340844)