## md cheatsheet 

<details>
  
<summary>srcs:</summary>

<a href="https://daringfireball.net/projects/markdown/">original John Gruber docs</a><br>
  
<a href="https://www.markdownguide.org">markdownguide.org</a><br>

<a href="https://docs.github.com/en/get-started/writing-on-github">github md-docs</a><br>
<a href="https://github.github.com/gfm/">github flavored markdown spec(gfm)</a><br>

<a href="https://github.com/mundimark/awesome-markdown">@mundimark/awesome-markdown </a> - A collection of markdown goodies (libraries, services, editors, tools, cheatsheets, etc.)<br>
<a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet">@adam-p/markdown-here/wiki/Markdown-Cheatsheet</a><br>
</a>

<a href="https://www.markdowntutorial.com/">markdowntutorial.com</a> - interactive lesson<br>

http://markdown.pioul.fr - md online editor

</details>

<br>





### Basic Syntax  
*Elements outlined in original design document. All Markdown applications support these elements.*

- Paragraphs  ```blank line to separate one or more lines | <p>```
- Line Breaks `end a line with two or more spaces "trailing whitespace" | <br>`
<br>

- Headings ```# 6 lvls | alt-syntx:line-below h1:== h2:--```
- Emphasis `**bold**, *italic*, ***bolditalic*** | (* for cmptblt in the middle)`
- Horizontal Rules `***, ---, ___ (put blank line bfr and aftr)`  
- Escaping Characters `\`
<br>  
  
- Blockquote `Nested | w other elements | (put blank-line before and aftr)`
- Lists `Ordered, Unordered, Mixed, Nested, w other eElements(use four spaces or one tab)`       
- Codeblocks ``inline`(use boublebackticks if backticks in code) | Codeblock(three-backticks)(extended syntax) ``  
- Links `url/emails | to heading-id | reference-style | titles | %20-for-spaces` 
- Images `![pic](txt"title)" | [![pic-link]()]) )` 
<br>

- HTML `use blank-lines to separate blocks! | you can't use md-syntx inside html blooks!`




<br>

### Extended Syntax  
*These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.*
+ Tables
+ Fenced Code Block \`\`\`
+ Footnote 	`[^1] [^1:]`  
+ Heading ID(anchror-links) `### My Great Heading {#custom-id}`
+ Definition List `term<br> : definition`
+ Strikethrough `~~The world is flat.~~`
+ Task List `-[] -[x]`
+ Emojis `copy/paste | :shortcodes:`
+ Highlight `==very important words==`
+ Subscript `H~2~O | <sub></sub>`
+ Superscript `X^2^ | <sup></sup>` 
+ Automatic URL Linking `wrap link in backtiticks to disable`
+ Disabling Automatic URL Linking




<br>

### Hacks
*Workarounds for things not officially supported by Markdown.*
+ Underline `</ins>`
+ Indent `<&nbsp> (last resort option!)`
+ Center `by tables | </center>`
+ Color `<font color="red">This text is red!</font>`
+ Comments `[coment]: # | [//]: # "Comment" | [//]: # (Comment) | <!-- comment -->`
+ Admonitions `> :memo: **Note:** Sunrises are beautiful.`
+ Image Size `<img src="image.png" width="200" height="100">`
+ Image Captions `<figure><img alt=text=><figcation></figcaption></figure>`
+ Link Targets `<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>`
+ Symbols `(c), (r), etc...`
+ Table Formatting `<br>(inside cell), <ul><li>(inside cell)`
+ Table of Contents(if no suporting heading Ids) `[Underline](#underline)`
+ Videos `[![Image-alt-text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)`



<br>

### github flavored(ghf)

- collapsed section `</details></summary>`
- Colors call out `The background color should be `#ffffff` for light mode and `#0d1117` for dark mode`



