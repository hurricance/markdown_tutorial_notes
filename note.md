## Overview

learning notes from [markdownguide][1]

### Basic Syntax

#### Headings

From "#" to "######", represents \<h1\> to \<h6\>
Alternate syntax: on the line below the text, add "===" for h1 and "---" for h2

#### Paragraphs

just plain text, use blank line to seperate one or more lines, no need to indent

#### Emphasis

Bold: "**" or "__"
Italic: "*" or "_"
Code: "`"

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

### Extended Syntax

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
```md
```
``````


[1]: https://www.markdownguide.org/ 