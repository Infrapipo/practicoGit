# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

Heading rules
-------------
-------------
-------------
# Emphasis
**This is bold text**

**This is bold text**

_This is italic text_

_This is italic text_

~~Strikethrough~~

# Blockquotes
> Blockquotes can also be nested
>>...by using additional greater-than signs right next to each other...
>>>or with spaces between arrows.

# Lists
Unordered
- Create a list by starting a line with `+`, `-`, or `*`
- Sub-list are made by identing 2 spaces:
    - Marker character change forces new list start:
        - Ac tristique libero volutpat at
        - Facilisis in prentium nisl aliquet
        - nulla volutpat aliquem velit
- Very easy!
Ordered
1. Primero
2. Segundo
3. Tercera
4. Cuarta
5. Quinta

Start numbering with offset

57. foo
58. bar

# Code
Inline code

indented code

```
//some comments
line 1 of code
line 2 of codes
line 3 code
```
Block code "fences"
 ```
 sample text here...
```
Syntax highlighting
```
'var' foo = **function** (bar) {
    **return** bar++;
};

console.log(foo(5));
```
# Tables
| **Option** | **Description** |
| ----------- | -----------------|
| data| path to data files
| engine | engine to be used for precessing templates.
| ext | extension to be used for dest files.

Right aligned columns

| **Option** | **Description** |
| :---   | ---:                |
| data   | path to data files  |
| engine | engine to be used for precessing templates.                     |
| ext    | extension to be used for dest files. |

# Links

[link text](https://www.jetbrains.com/help/objc/markdown.html#code-blocks)

[link with title](https://www.jetbrains.com/help/objc/markdown.html#code-blocks)

Autoconverted link https://github.com (enable linkify to see)

# Images
![imagen 1](../practicoGit/imagenes/devops1.jpg)

![imagen 2](../practicoGit/imagenes/git1.png)
Like links, Images also have a footnote style syntax

![imagen 3](../practicoGit/imagenes/vsc.png)

With a reference later in the document defining the URL location:

# Plugins
The killer feature of `markdown-it` is very effective support of syntax plugins.