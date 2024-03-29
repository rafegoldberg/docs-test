---
title: "Flavored Syntax"
slug: "syntax-extensions"
excerpt: "Specs and examples of ReadMe's (restrained) Markdown syntax extensions."
hidden: false
metadata: 
  image: []
  robots: "index"
createdAt: "Sat Mar 28 2020 12:11:36 GMT+0000 (Coordinated Universal Time)"
updatedAt: "Tue Apr 07 2020 14:57:55 GMT+0000 (Coordinated Universal Time)"
---
## Custom Blocks

### Code Tabs

A tabbed interface for displaying multiple code blocks. These are written nearly identically to a series of vanilla markdown code snippets, except for their distinct _lack_ of an additional line break separating each subsequent block. [**Syntax & examples**.](doc:code-blocks)

### Callouts

Callouts are very nearly equivalent to standard Markdown block quotes in their syntax, other than some specific requirements on their content: To be considered a “callout”, the block quote must start with an initial emoji, which is used to determine the callout's theme. [**Syntax & examples**.](doc:callouts)

### Embeds

Embedded content is written as a simple Markdown link, with a title of "@embed". [**Syntax & examples**.](doc:embeds)

## Standard Markdown

The engine also supports all standard markdown constructs, as well as CommonMark options, and most GitHub syntax extensions.

- [**Tables**](doc:tables) <!-- Supports GFM-style table alignment. -->
- [**Lists**](doc:lists) <!-- Ordered and unordered lists; GFM-style checklists. -->
- [**Headings**](doc:headings) <!-- Supports setext, underline, and compact notations. -->
- [**Images**](doc:images)
- **Decorations** (link, strong, and emphasis tags, etc.)
