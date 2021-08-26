# MARKDOWN
- **Lightweight markup language** with a plain text formatting syntax
- Can be converted into HTML/XHTML and other formats
- It's main purpose is readability and ease of use


## What Is It Used For?
- Readme Files (like this document)
- Forum $ Blog Posts
- Used in Many Static Site Generators

Things You Can Format (not all listed):
- Headings
- Lists
- Emphasis
- Links
- Blocks of Code
- Images
- Blockquotes
- Horizontal Rules
- Tables

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
* This text* is italic
_This text_ is italic

<!-- Strong -->
**This is** strong
__this text__ is italic

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal Rule -->
---
____

<!-- Blockquote -->
> this is a quote

<!-- Links -->
[Hashicorp](http://hashicorp.com)

<!-- Unordered Lists -->
* Item1
* Item2
* Item3
  * Nested Item1
  * Nested Item2

<!-- Tables of contents -->
1. Apple
   1. green
   2. red
2. Orange
3. Banana

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`

<!-- Images -->
![Markdown Logo](https://www.hashicorp.com/favicon.svg)


<!-- Github Markdow -->

Install unzip: `sudo apt-get install unzip`

<!-- Code Blocks -->

```bash
# bash script
npm install
npm start```

```javascript
# javascript function
    function add(num1, num2) {
        return num1 + num2;
    }
```

```python
# Python function
    def add (num1, num2):
        return num1 + num2
```

<!-- Task Lists -->
* [x] Task1
* [x] Task2
* [ ] Task3 

<!-- Tables -->
| Name | Email |
| ----: | :----- |
| Ion   | ion@hashicorp.com |
| office | office@acme.com |


<details>
    <summary> Section Header</summary>
    Section BODY
    - item1
    - item2


<!-- Foot notes -->

[^1]: By Ion Ermurachi
