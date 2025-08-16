---
layout: post
title: My guide to Markdown
subtitle: 
tags:
  - markdown
  - writing
  - productivity
  - coding
  - formatting
  - beginners
  - notetaking
  - programming
  - github
  - plaintext
  - markup
  - learning
  - writing
author:
  - Sean
---
During my brief IT studies in an introduction to programming unit we had to write documentation for all of our code. The documentation along with comments explain what your code does so that other people can use it. The reason is that other people will have to use your code and if it is used in something critical to a service or business it is like infrastructure.

Online this documentation is writen in Markdown. At first I thought it was just a thing I'd use in that course. Then I found that the language was already in use extensively on the internet.

Markdown was created by John Gruber, to be able to be easily converted into HTML or other formats and displayed easily in web browsers. While also being easy to write.

It gets around the unwieldy use of tags for formatting.
``` html
<b>BOLD</b>
```
And the need to select and format text like in traditional word processing programs.
### Why learn Markdown?

- It only takes about 10 minutes to learn and get used to.
- Easily convertible to other formats.
- Readable without special software.
- Once you learn it there's less friction writing your thoughts because you don't have to take your hands off the keyboard.
- Is just a regular text (.txt) file with a different extension. (.md)

You aren't learning a limited skill that is easy to pick up, it's one that is transferable.

- Microsoft word supports pasting sources that are markdown, but not writing in it.
-  Libre Office is working on Markdown integration at time of writing.
- In windows 11 notepad has the option to use it.
- Large language models give their output in Markdown so you can make sense of their output if you copy and paste from them.
- Github extensively uses markdown for code documentation.

A limited type of markdown is used for:
- Google suite programs, have support writing in it but not handling the files.
- Social apps like Facebook, Discord, Reddit, YouTube comments, Whatsapp.

## How to use it:
For me when I got started the most helpful thing was headings. Just like in a word processor they make it easier to outline a document and come back to a section.

```Markdown
# Title 
## Subheading 
### Subheading
```
Gives you:
# Title
## Subheading 
### Subheading

For me this was great as you could type out a document outline quickly to plan it out before the ideas left my head. 

Then formatting:
``` Markdown
*Italic*
**Bold**
***Italic and Bold***
```
Gives you:

*Italic*

**Bold**

***Italic and Bold***

And then as I got going was lists

```Markdown
- Item 1
- Item 2
- Item 3

1. Item 1
2. Item 2
3. Item 3
```
Gives you:

- Item 1
- Item 2
- Item 3

1. Item 1
2. Item 2
3. Item 3

That seemed to cover 80% of my needs. There are other options, but it depends on where you are typing your markdown.

Then some apps allow for tables to be created, but it depends on the app.

```Markdown

| Header 1 | Header 2 |
|---|---|
| Cell 1 | Cell 2 |
```
Gives you:

| Header 1 | Header 2 |
|---|---|
| Cell 1 | Cell 2 |

Finally there are code blocks

Using three ~ (Tildes) or three ' (Called back ticks) at the first line and three at the last line allows for separate display of code or just easy copyable segments.

I'm writing this in a markdown editor so in order to show a code block inside a code block, you simply put " \ " in front of the markdown formating.

Beside the three tildes you can write the programing language used as well.

So typing:

\~~~ Markdown 
Code goes here
\~~~

Gives you:
```Markdown

Code goes here

```


Finally there are hyperlinks
```Markdown

[Link Text](https://example.com/your-link-here)
```

Gives you:

[Link Text](https://example.com/your-link-here)

Each platform has its slight differences so it's worth googling their markdown support pages, but the above examples cover most things I use.

If you are interested you can try it out on this [website](https://markdownlivepreview.com/)

It shows you both what you are writing and how it is rendered in a web browser.

