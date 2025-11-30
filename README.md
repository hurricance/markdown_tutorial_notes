## Overview

learning notes from [markdownguide][1]

[1]: https://www.markdownguide.org/ 

### Table of Contents

- [Basic Syntax](#basic-syntax)
- [Extended Syntax](#extended-syntax)
- [Summary](#summary)
- [External Resources](#resources)

### Basic Syntax {#basic-syntax}

#### Headings

From "#" to "######", represents \<h1\> to \<h6\>  
Alternate syntax: on the line below the text, add "===" for h1 and "---" for h2

#### Paragraphs

just plain text, use blank line to seperate one or more lines, no need to indent

#### Emphasis

- Bold: "**" or "__"  
- Italic: "*" or "_"  
- Code: "`"
    - to escape backticks, enclose the word or phrase in double backticks
      ```md
      ``use `code` to display this``
      ```

#### Blockquotes

use ">", also can be used for multiple lines, for nested blockquotes, use ">>"

#### Lists

Ordered lists: 
```md
1. apple
2. banana
3. orange
``` 
<br>

Unordered lists:
```md
* apple
* banana
* orange
or
- apple
- banana
- orange
or
+ apple
+ banana
+ orange
```

#### Horizontal Rules

"---" or "___" or "***"

#### Links

##### General Usage
```md
[text](link)
adding titles: [text](link "title")
```

##### Formatting Links:

```md
Bold: **[text](link)**
Italic: *[text](link)*
Code: [`text`](link)
```

##### Reference-style Links
```md
[text][1]
[1]: link "title"
```

#### Images

##### General Usage

```md
![text](link "title")
```

##### Linking Images

```md
[![text](link "title")](link)
```

#### Escaping Characters
use "\"

characters you can escape
```text
\ blackslash
` backtick
* asterisk
- underscore
{} curly brackets
[] brackets
<> angle brackets
() parentheses
# pund sign
+ plus sign
- minus sign
. dot
! exclamation mark
| pipe
```

### Extended Syntax {#extended-syntax}

#### Tables

##### General Usage

```md
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |
```

##### Alignment

```md
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

#### Fenced Code Block

``````md
```language
```
``````

#### Footnotes

```md
this is a simple footnote example[^1]
[^1]: this is a footnote
```

#### Heading IDs

```md
### this is a heading {#heading-id}

linking to this heading:
[this is a link](#heading-id)
```

#### Definition Lists

```md
Apple
: this is a kind of fruits
```

#### Strikethrough

```md
~~through~~
```

#### Task Lists

```md
- [x] apple
- [ ] banana
```

#### Emoji

```md
:joy:
```

#### Highlight

```md
==highlight==
```

#### Subscript

```md
H~2~O
```

#### Superscript

```md
x^2^
```

### Summary {#summary}


### Useful External Resources Link {#resources}

- [GitHub Flavored Markdown](https://github.github.com/gfm/)
- [Table Generator](https://www.tablesgenerator.com/markdown_tables)
- [Html Entities Reference List](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references)
- [List of Emoji ShortCodes](https://gist.github.com/rxaviers/7360908)
