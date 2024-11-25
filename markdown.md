# **_Basic Syntax_**
---
`code` ````` not''''' (next to 1)

## CODE

```
inline `code`

\``` x3 before and after \``` x3 for block code (using backslash to escape character that would be used to format text)
```
### Output

inline `code`

\``` x3 before and after \``` x3 for block code (using backslash to escape character that would be used to format text)


## Fenced Code Block

```
{
"firstName": "John",
"lastName": "Smith",
"age": "245"
}
```
### Output

{
"firstName": "John",
"lastName": "Smith",
"age": "245"
}


## Syntax Highlighting

```
\```language
// code
\```
```
### Output

```
language
// code
```


## Headings
Do this `# heading` not this `#heading`
```
# heading 1

## heading 2

### heading 3

#### heading 4

##### heading 5

###### heading 6
```
### Output

# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

## Alternative Syntax
```
heading 1
================

heading 2
----------------
```
### Output

heading 1
================

heading 2
----------------

## Paragraphs
Use a BLANK line to separate lines of text to create a PARAGRAPH

```
First line.

Second line.
```

### Output

First line.

Second line.

## Line Breaks
To create a line break or new line `(<br>)`, end a line with 2 or more SPACES then type RETURN

```
First line.
Second line.
```

### Output

First line.  
Second line.


## Italics

```
*Italics*

_Italics_

An*Italics*Lesson
```
### Output

*Italics*

_Italics_

An*Italics*Lesson  
Do this `An*Italics*Lesson` not this `An_Italics_Lesson`

## Bold Text

```
**Bold Text**

__Bold Text__

Be**Bold**Now
```
### Output

**Bold Text**

__Bold Text___

Be**Bold**Now  
Do this `Be**Bold**Now` not this `Be__Bold__Now`

## Bold and Italics

```
***Bold Italics***

___Bold Italics___

__*Bold Italics*__

**_Bold Italics_**

B***old***Italics
```

### Output

***Bold Italics***

___Bold Italics___

__*Bold Italics*__

**_Bold Italics_**

B***old***Italics  
Do this `B***old***Italics` not this `B___old___Italics`


## Blockquote
Put BLANK lines BEFORE and AFTER blockquotes

```
> Blockquote
```

### Output

> Blockquote

## Blockquotes with Paragraphs
Add a > on the blank line between paragraphs

```
> Paragraph 1
>
> Paragraph 2
```

### Output

> Paragraph 1
>
> Paragraph 2

## Nested Blockquotes

```
> Blockquote
>
>> Nested Blockquote
```

### Output

> Blockquote
>
>> Nested Blockquote


## Blockquotes with Other Elements

```
> #### heading 4
>
> - Unordered
> - List
>
> *Italics* **Bold** ***Bold Italics***
```

### Output

> #### heading 4
>
> - Unordered
> - List
>
> *Italics* **Bold** ***Bold Italics***


## Ordered List

```
1. first
2. second
3. third
4. etc
---
1. first
1. second
1. third
1. etc
---
1. first
6. second
2. third
9. etc
---
1. first
2. second
3. third
    1. Indented first
    2. Indented second
4. etc
---
```

### Output

1. first
2. second
3. third
4. etc
---
1. first
1. second
1. third
1. etc
---
1. first
6. second
2. third
9. etc
---
1. first
2. second
3. third
    1. Indented first
    2. Indented second
4. etc
---

**2 `TAB`s for indent**

## Unordered List

```
- first
- second
- third
- etc
---
* first
* second
* third
* etc
---
+ first
+ second
+ third
+ etc
---
- first
- second
- third
    - Indented first
    - Indented second
- etc
---
```

### Output

- first
- second
- third
- etc
---
* first
* second
* third
* etc
---
+ first
+ second
+ third
+ etc
---
- first
- second
- third
    - Indented first
    - Indented second
- etc
---

## Ordered and Unordered List Nesting

```
1. first
2. second
3. third
    - Unordered first
    - Unordered second
4. etc
---
- first
- second
- third
    1. Ordered first
    2. Ordered second
- etc
---
```

### Output

1. first
2. second
3. third
    - Unordered first
    - Unordered second
4. etc
---
- first
- second
- third
    1. Ordered first
    2. Ordered second
- etc
---


## Horizontal Rule
```
---
***
___
```
### Output
---
***
___

## Link (and Title "with description")

```
[title](https://blahblah.com "This is the description")
```
### Output

[title](https://blahblah.com "This is the description")


## URLs and Email Addresses

```
<https://www.markdownguide.org>
<fake@email.com>
```

### Output

<https://www.markdownguide.org>   
<fake@email.com>


# Formatting Links
## The First Part
```
[link][1]
[link] [1]
```
### Output

[link][1]   
[link] [1]

## The Second Part
```
[1]: https://blahblah.com
[1]: https://blahblah.com "blah"
[1]: https://blahblah.com 'blah'
[1]: https://blahblah.com (blah)
[1]: <https://blahblah.com> "blah"
[1]: <https://blahblah.com> 'blah'
[1]: <https://blahblah.com> (blah)
```
### Output
**Not Shown**

[1]: https://blahblah.com
[1]: https://blahblah.com "blah"
[1]: https://blahblah.com 'blah'
[1]: https://blahblah.com (blah)
[1]: <https://blahblah.com> "blah"
[1]: <https://blahblah.com> 'blah'
[1]: <https://blahblah.com> (blah)

## Links in Text
```
Text here [blah](https://blahblah.com "blah") text after   
Text here [blah][1] text after   
[1]: <https://blahblah.com> "blah"
```
### Output

Text here [blah](https://blahblah.com "blah") text after   
Text here [blah][1] text after   
[1]: <https://blahblah.com> "blah"

### Additional

HTML link would be `<a href="https://blahblah.com" title="blah">blahblah</a>`

any spaces fill them with %20 and parentheses inside (), with %28 for (, and %29 for).

## Image

```
![alt text](image.jpg)
[![alt text](image.jpg)](imagelink.com)
```
### Output

![alt text](image.jpg)   
[![alt text](image.jpg)](imagelink.com)


# Extended Syntax

## Table

```
| Syntax | Description |
|--------------|--------------|
| Header | Title |
| Paragraph | Text |
```

### Output

| Syntax | Description |
|--------------|--------------|
| Header | Title |
| Paragraph | Text |


## Footnote
```
Here's a sentence with a  footnote. [^1]
[^1]: this is the footnote
```
### Output

Here's a sentence with a  footnote. [^1]
[^1]: this is the footnote

## Heading ID

```
### My Great Heading {#custom-id}
```

### Output

### My Great Heading {#custom-id}


## Definition List

```
term
: definition
```
### Output

term
: definition

## Strikethrough
```
~~Strike this~~
```

### Output

~~Strike this~~


## Task List

```
- [x] Check this box
- [ ] Check this box
- [ ] Don't check this box
```

### Output

- [x] Check this box
- [ ] Check this box
- [ ] Don't check this box


## Emoji

```
:joy:   2 or more spaces after for new line   
:cup_with_straw:   
:aquarius:
or you get this
:joy:
:cup_with_straw:
:aquarius:
```
### Output

:joy:   2 or more spaces after for new line   
:cup_with_straw:   
:aquarius:   
or you get this   
:joy:
:cup_with_straw:
:aquarius:


## Highlight
```
<mark>HighLIGHT</mark>
```

### Output

<mark>HighLIGHT</mark>


## Subscript
**REMEMBER** `<sub></sub>` ~~**NOT**~~ `<sub/>`
```
H<sub>2</sub>SO<sub>4</sub>
H<sub>2<sub>SO</sub>4</sub>4
```
### Output

H<sub>2</sub>SO<sub>4</sub>   
H<sub>2<sub>SO</sub>4</sub>4


## Superscript
**REMEMBER** `<sup></sup>` ~~**NOT**~~ `<sup/>`
```
X<sup>2</sup>   
X<sup>2<sup>2</sup>2</sup>2
```
### Output

X<sup>2</sup>   
X<sup>2<sup>2</sup>2</sup>2

## Escaping Characters
```
You can use \\backslash to escape the following characters
|Character|Name|
|---------|---------|
|\\   |backslash|
|\`|backtick|
|\*|asterisk|
|\_|underscore|
|\{}|curly braces|
|\[]|brackets|
|\<>|angle brackets|
|\()|parentheses|
|\#|hashtag or pound sign|
|\+|plus sign|
|\-|minus sign (hyphen)|
|\.|dot|
\!|exclamation mark|
|\|   |pipe|
```

You can use \\backslash to escape the following characters
|Character|Name|
|---------|---------|
|\\   |backslash|
|\`|backtick|
|\*|asterisk|
|\_|underscore|
|\{}|curly braces|
|\[]|brackets|
|\<>|angle brackets|
|\()|parentheses|
|\#|hashtag or pound sign|
|\+|plus sign|
|\-|minus sign (hyphen)|
|\.|dot|
|\!|exclamation mark|
|\|   |pipe|
