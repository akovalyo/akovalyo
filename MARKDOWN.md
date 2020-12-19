# [Markdown](https://daringfireball.net/projects/markdown/)
*text-to-HTML conversion tool*

**[GitHub Markdown info page](https://help.github.com/en/github/writing-on-github)**

***
* :+1:[Emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md):vulcan_salute:
* <a href="#headers">Headers</a>
* [Phrase emphasis](#phrase emphasis)
* <a href="#lists">Lists</a>
* <a href="#text">Dropdown text</a>
* <a href="#links">Links</a>
* <a href="#code">Code blocks</a>
* <a href="#hrz">Horizontal rule</a>
* <a href="#tables">Tables</a>
* <a href="#images">Images</a>
* <a href="#va">Video and audio</a>
* <a href="#va">Ignoring Markdown formatting</a>


***

## Headers
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

***

## Phrase emphasis
```
Italics *text* or _text_
Bold **text** or __text__
Combined **text _text_** or _text **text**_
Strikethrough ~~text~~
```
Italics *text* or _text_

Bold **text** or __text__

Combined **text _text_** or _text **text**_

Strikethrough ~~text~~

***

## Lists

**Unordered (bulleted) lists**
```
* One
* Two

+ One
+ Two

- One
- Two

or

* One
* Two
  * Abc
  * Abc
    * 123
    * 123
```

* One
* Two

+ One
+ Two

- One
- Two

or

* One
* Two
  * Abc
  * Abc
    * 123
    * 123
***

**Checklist**
```
- [x] One
- [ ] Two
- [ ] Three
```

- [x] One
- [ ] Two
- [ ] Three

***

**A list item with a blockquote**

``` 
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
```
*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
***

**A list item with a code block**
To put a code block within a list item, the code block needs to be indented twice — 8 spaces or two tabs

```
*   A list item with a code block:

        <code goes here>
```

*   A list item with a code block:

        <code goes here>
        
***

**Ordered (numbered) lists**
```
1. One
2. Two
3. Three
```

1. One
2. Two
3. Three


*It’s worth noting that it’s possible to trigger an ordered list 
by accident, by writing something like this:*


1986. What a great season.


*In other words, a number-period-space sequence at the beginning of
a line.To avoid this, you can backslash-escape the period:*

`1986\.`

1986\. What a great season.


***

## Text

**Dropodown text**

```
<details>
	<summary>Title</summary>
 
[4 spaces (tab) befor for indented line]
     TextTextTextTextTextText
     TextTextTextTextText
     TextTextTextText
     TextTextText
     TextText
     Text
 
 </details>
 
 ```
 
 <details>
	<summary>Title</summary>
 
     TextTextTextTextTextText
     TextTextTextTextText
     TextTextTextText
     TextTextText
     TextText
     Text
 
 </details>
 
 ***

## Links

**Automatic links**
```
<http://github.com/>
```

<http://github.com/>


**Inline**
```
This is inline [link](http://github.com/).
```
This is inline [link](http://github.com/).


**With a title**
```
This is inline [link](http://github.com/ "With a title").
```
This is inline [link](http://github.com/ "With a title").


**Reference link**
```
Reference [link][1] which you [define][2] elsewhere in your [document][3].

[1]: http://github.com/   "One"
[2]: http://github.com/   "Two"
[3]: http://github.com/   "Three"
```

Reference [link][1] which you [define][2] elsewhere in your [document][3].

[1]: http://github.com/   "One"
[2]: http://github.com/   "Two"
[3]: http://github.com/   "Three"

***

## Code blocks

```
Inline `code` has `back-ticks` around it.
```

Inline `code` has `back-ticks` around it.


Blocks of code are either fenced by lines with three back-ticks \`\`\`, or are indented with
four spaces (1 tab). I recommend only using the fenced code blocks --
they're easier and only they support syntax highlighting.

\`\`\`javascript

var s = "JavaScript syntax highlighting";
alert(s);

\`\`\`

\`\`\`python

s = "Python syntax highlighting"
print s

\`\`\`

\`\`\`

No language indicated, so no syntax highlighting. 

\`\`\`

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
```

Shell:      console, shell
Bash:       bash, sh, zsh
Powershell: powershell, ps
Dos:        dos, bat, cmd


***

## Horizontal rule

```
* * *

***

*****

- - -

---------------------------------------
```

***

## Tables

```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

***

## Images

```
![GitHub](https://i.pinimg.com/600x315/2c/b6/70/2cb670b6ddd8922a1c1b2fee4f6f758c.jpg)
```
![GitHub](https://i.pinimg.com/600x315/2c/b6/70/2cb670b6ddd8922a1c1b2fee4f6f758c.jpg)   

***

## Video and audio

* **Variant 1** - Video from youtube

```
[![Alt text](https://img.youtube.com/vi/VID/0.jpg)](https://www.youtube.com/watch?v=VID)
```
*VID is youtube ID*


* **Variant 2** - Embedded video and audio

```
![](filename.mp4)
```

```
![](filename.mp3)
```

## Ignoring Markdown formatting

To ignore Markdown formatting use ```\``` before the Markdown character.

```
\*Hello World\*
```

\*Hello World\*

