
# Craft Blog Boilerplate

## Description

A Boilerplate for blog / general interior sections, for use with Craft CMS.

## Installation

First, import the Article Matrix Field using the [Art Vandelay Plugin](https://github.com/xodigital/ArtVandelay) plugin, and the `article-field.json` file.

Then, simply place the components directory within `craft/templates/`, and incorporate the included stylesheet.

## Usage

```twig
...
{% include "_components/article.html" %}
...
```

Assuming that the included .json file has been used to import the Article Matrix Field, via the [Art Vandelay Plugin](https://github.com/xodigital/ArtVandelay).

---

## Block Types

### Body Text
A simple block for body text.

Fields:
+ Text

### Heading
A simple heading for separating sections.

Fields:
+ Text

### Video Block
A video block that can be sourced from a video in Crafts assets, or an external embed link.

Fields:
+ Video
+ Caption
+ Position (Left, Right, Center, Full Width)
+ Embed Source - accepts iframe embed link, and is mutually exclusive with Video

### Image Block
A block for images, sourced from Crafts assets

Fields
+ Image
+ Caption
+ Position (Left, Right, Center, Full Width)

### Quote Block
A block for quoted text

Fields
+ Quote
+ Position (Left, Right, Center, Full Width)
+ Byline

### Accent Color
A block for specifying an accent color - currently only applies a stylish partial border to Quote Blocks.

Fields:
+ Color

---
## Example
![Demo of the Matrix Field][logo]

[logo]: https://gitlab.newmediacampaigns.com/samleblanc/craft-blog-boilerplate/raw/master/examples/demo.gif "Demo of the Matrix Field"



