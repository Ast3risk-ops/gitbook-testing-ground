---
description: Page content here.
icon: markdown
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# Markdown

Comment

***

### Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,, -- ---

"Smartypants, double quotes" and 'single quotes'

### Emphasis

**This is bold text**

**This is bold text**

_This is italic text_

_This is italic text_

_**Italic and bold**_

~~Strikethrough~~

<mark style="background-color:blue;">Coloured</mark>

<mark style="color:blue;">Coloured</mark>

### Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.

### Lists

Unordered

* Create a list by starting a line with `+`, `-`, or `*`
* Sub-lists are made by indenting 2 spaces:
  * Marker character change forces new list start:
    * Ac tristique libero volutpat at
    * Facilisis in pretium nisl aliquet
    * Nulla volutpat aliquam velit
* Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. You can use sequential numbers...
5. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
58. bar

Task:

* [ ] 1
* [x] 2
* [ ] 3



### Code

Inline `code`

Indented code

```
// Some comments
line 1 of code
line 2 of code
line 3 of code
```

Block code "fences"

```
Sample text here...
```

Syntax highlighting

```js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

### Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

### Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/)

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

### Images

![Minion](https://octodex.github.com/images/minion.png) ![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg)

Like links, Images also have a footnote style syntax

![Alt text](https://octodex.github.com/images/dojocat.jpg)

With a reference later in the document defining the URL location:

#### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :cry: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.

#### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

* 19^th^
* H~~2~~O

#### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++

#### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

\==Marked text==

#### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^1].

Footnote 2 link[^2].

Inline footnote^\[Text of inline footnote] definition.

Duplicated footnote reference[^2].

#### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

: Definition 1\
with lazy continuation.

Term 2 with _inline markup_

: Definition 2

```
    { some code, part of Definition 2 }

Third paragraph of definition 2.
```

_Compact style:_

Term 1\
\~ Definition 1

Term 2\
\~ Definition 2a\
\~ Definition 2b

#### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

\*\[HTML]: Hyper Text Markup Language

[^1]: Footnote **can have markup**

    and multiple paragraphs.

[^2]: Footnote text.
