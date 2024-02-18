---
title: "Lists"
slug: "lists"
excerpt: ""
hidden: false
metadata: 
  image: []
  robots: "index"
createdAt: "Tue Dec 10 2019 01:01:15 GMT+0000 (Coordinated Universal Time)"
updatedAt: "Wed Oct 25 2023 17:26:38 GMT+0000 (Coordinated Universal Time)"
---
## Syntax

```shell Bullet Lists
- Item Zed
  - Nested Item # indented 2 spaces
* Item Alt      # alternate bullet syntax
```
```shell Numeric Lists
1. Item Zed
   1. Nested Numeric # indented 3 spaces
2. Item One
```
```shell Check Lists
- [ ] Open Item
- [x] Item Done
```

## Examples

<details open>
  <summary><em>Bulleted List</em></summary><hr>

- Item Zed
  - Nested Item
  - Nested Item
- Item One
- Item Two

<hr></details>
<details>
  <summary><em>Ordered List</em></summary><hr>

1. Item Zed
   1. Nested Numeric
   2. Nested Numeric
2. Item One
3. Item Two

<hr></details>
<details>
  <summary><em>Check List</em></summary><hr>

- [ ] Task Zed
- [x] Task One
- [ ] Task Two

</details>

## Edge Cases

### Split Lists

Seamlessly insert content blocks in between list items:

1. Item Zed

   > Sit excepturi doloremque deserunt maiores quam voluptatibus cupiditate delectus perferendis, ratione cum impedit rem recusandae inventore quibusdam et, tenetur aspernatur asperiores reiciendis soluta.

2. Item One

   ```javascript
   console.log('hello world')
   ```

3. Item Two

### Auto-Ordering

Writing this will yield a properly ordered list:

```
1. Item Zed
1. Item One
1. Item Two
```

Starting an ordered list with any number will increment continuously from that point, like so:

98. Starting in media res
99. Another list item
100. Yet another item

[block:html]
{
  "html": "<style>\n  summary {\n    padding-top: 8px;\n    outline: none !important;\n    user-select: none;\n  }\n  details[open] + details > summary {\n    padding-top: 0;\n  }\n  details > summary + hr {\n    opacity: .66;\n  }\n</style>"
}
[/block]
