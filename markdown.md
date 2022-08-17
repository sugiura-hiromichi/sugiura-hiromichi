## sub repo project
[notions](notions/)

# index.md

i want to learn markdown
maybe

## sub heading

in sub heading #dont do this

insert blank line to change paragraph. 
keep lines left-aligned like this

to create a line break or new line,  
end a line with two or more spaces,  
and then type return.

# Emphasis

## Bold

To bold text, add two asterisks or underscores  
**like tihs**. __underscore__.
**asterisk**.  

## Italic

To italicize text, add one asterisk or undersocre before and after a word or phrase.  
To italicize the middle of a word for emphasis, add one asterisk without spaces.  
*itaic* *itaic* _italic_ *italic*  

## Bold and Italic

***three asterisks!!***

# Blockquotes

to create a blockquote, add a > in front of a paragraph.  

>like this
like this. 
like this

if you want to end quotion, insert blank line.

>Add a > on the blank lines between the paragraph
>
>it allows multiple para blockquotes.  
**like this!**

## Nesting

>we can nest blockquotes
>>by increasing > in front of line.  
>
>exit nesting with line which only have > on their head.  

## with Other Elements

Blockquotes can contain other Markdown formatted elements.  
*Not all

>### Heading level3
>- revenue was off the cahrt. 
>
>*Everything* is go**ing** accurately. 

# Lists

You can organize items into ordered and unordered lists.

## Ordered Lists

To create an ordered list, add line items with numbers followed by periods.  
The numbers don't have to be in numerical order, but the list should start with the number one.
1. first item
1. second item
    1. indented first
    1. indented second.  

Insert blank line to exit list. 

## Unordered Lists

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items.  
Indent one more items to create a nested list.

- first
- second
- third
    - indented first
    - indented second
        - more indented

insert blank line to exit unordered list

## Starting Unordered List Items with Numbers

- 1968\.

## Adding Elements in Lists

- This is the first list item
sa
- this is the second list item.  
indent indent indent
    > A blockquote would  
    
- Code

        let a = 9;

### Image

1. Open the file containing
2. Marvel at its beauty

    ![Tux, the Linux mascot]

3. Close the file

## Lists

You can nest an unordered list in an ordered list, or vise versa.  

1. f
2. s
    - nested
    - two
3. ?

# Code

At the command prompt, type

```rust
let a = 0;
match a{
    c if true=>c,
    b @ 0..=8=>b,
    _=>a
}
```

## Escaping Backticks

``Use `code` in your Markdown file.``

# Code Blocks

To create code blocks, indent every line of the block by at least four spaces or one tab.

    let nv=Command::new();
    for i in 0..2{
        println!("{i}")
    }

Like this 

# Horizontal Rules

To create a horizontal rule, use three or more asterisks, dashes, or underscores on a line by themselves.  

---

This is horizontal rule:D

# Links

- It's the most efficient way to get modern "website" outlook. 

---

To create a link, enclose the link text in brackets and then 
follow it immediately with the URL in parentheses.  
This is [Link!!](https://github.com/ww0l/playground)

## Adding Titles

You can optionally add a title for a link. This will appear as a tooltip when 
the user hovers over the link. To add a title, enclose it in quotiation marks after the URL.

[Where is here?](https://github.com/ww0l/playground "this is my tiny playground")

# URLs and Email Addresses

To quickly turn a URL or email into a link, enclose it in angle brackets. 
<https://twitter.com/9kv8xiyi10> Like this.

# Formatting Links

To emphasize links, add asterisks before and after the backest and parentheses.
To denote links as code, add backticks in the brackets.

**[Bold Link](https://github.io/ww0l/github_pages)**
*[Italic Link](https://www.nicovideo.jp "nicovideo.jp")*
denote links as ['code'](#code)

# Reference-Style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown.
Reference-style links are constructed in two parts: the part you keep inline with your text
and the part you store somewhere else in the file to keep the text easy to read.

## Formatting the First Part of the Links

The first part of a reference-style link is formatted with two sets of brackets.
The first set of brackets surrounds the text that should appear linked.
The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets.
The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

[like this][ref]

[ref]:https://github.com/ww0l "hello"

# Images

To add an image, add an exclamation mark (!), followed by alt text in brackets,
and the path or URL to the image asset in parentheses.
You can optionally add a title in quotation marks after the path or URL.

![my icon picture. maybe](src/icon.png)

## Linking Images

To add a link to an image, enclose the Markdown for the image in brackets,
and then add the link in parentheses.

[![my icon again..](src/icon.png "icoooon")](https://github.com/ah-y)

# Escaping Characters

to display a literal character that would otherwise be used to format text in a
Markdown document, add a backslash (\) in front of the cahracter  
\* without the backslash, this would be an unordered list

# HTML

Many Markdown applications allow you to use HTML tags in Markdown-formatted text. 
This is helpful if you prefer certain HTML tags to Markdown syntax.
For example, some people find it easier to use HTML is also helpful when you need to
change tha attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your markdown-formatted file.

>This **word** is bold. This <em>word</em> is italic.

# HTML Best Practices

For security reasons, not all Markdown applications support HTML in Markdown documents.
When in doubt, check your markdown application's documentation.
Some applications support only a subset of HTML tags

---

# Extra syntax

---

# Tables

to add a table, use three or more hyphns to create each column's header,
and use pipes (|) to separate each column.
For compatibility, you should also add a pipe on eihter end of the row.

|Syntax|Desc|
|---:|:---:|
|Head|Til|
|Paragraph|Text|
|Table|`2D`|

you can align by adding a colon (:) to the reft, right, or both

# Footnotes

This is footnotes[^1]

[^1]: This is the first footnote

# Check Box

- [ ] this is check box which is not checked
- [x] this is check box which is checked
