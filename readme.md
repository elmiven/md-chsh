## md cheatsheet 

<details>
<summary>srcs:</summary>
<a href="https://daringfireball.net/projects/markdown/">original John Gruber docs</a><br>
<a href="https://www.markdownguide.org">markdownguide</a><br>
<a href="https://docs.github.com/en/get-started/writing-on-github">github-md-docs</a><br>
<a href="https://github.github.com/gfm/">github flavored markdown spec(gfm)</a><br>
<a href="https://www.markdowntutorial.com/">markdowntutorial.com</a><br>
<a href="https://github.com/mundimark/awesome-markdown"></a><br>
<a href="https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatshee"> </a><br>
<a href="https://gist.github.com/cuonggt/9b7d08a597b167299f0d"></a><br>
</details>
<br>





### Basic Syntax  
Elements outlined in original design document. All Markdown applications support these elements.

- Paragraphs `(<p> blank line to separate one or more lines)`
- Line Breaks `(<br> end a line with two or more spaces "trailing whitespace")`


   
- Headings `(# 6 lvls | alt-syntx:line-below h1:== h2:--)`
- Emphasis `(**bold**, *italic*, ***bolditalic*** | * for cmptblt in the middle)
- Horizontal Rules `(*** | --- | ___ | put blank line bfr and aftr)`  
- Escaping Characters `(\)`

- Blockquote  `(Nested | w other Elements | put blank-line before and aftr)`

- Lists (Ordered, unordered, nested, mixed, w other Elements( four spaces or one tab))       
- Codeblocks \`\`(inline, block)\`\`  
    
- Links (url/emails, to heading-id, reference-style, titles, %20-for-spaces) 

- Images `(![](txt"title" | [![]()]) )` 


- HTML (use blank-lines to separate blocj lvls, can't use md-syntx inside html blooks)




<br>

### Extended Syntax  
These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.


+ Tables
+ Fenced Code Block (\`\`\`)
+ Footnote 	`[^1] [^1:]`
  
+ Heading ID(anchror-links) 	`### My Great Heading {#custom-id}`

+ Definition List `(term<br> : definition)`
+ Strikethrough `~~The world is flat.~~`

+ Task List `(-[] -[x])`
+ Emojis `(copy/paste | :shortcodes:)`

+ Highlight `(==very important words==)`

+ Subscript `(H~2~O | <sub></sub>)`
+ Superscript `(X^2^ | <sup></sup>)` 

+ Automatic URL Linking `(wrap link in backtiticks to disable )`
+ Disabling Automatic URL Linking




<br>

### Hacks
Workarounds for things not officially supported by Markdown.


+ Underline `(<ins></ins>)`
+ Indent `(<&nbsp> (last resort option))`
+ Center `(tables | <center></center>)`
+ Color `(<font color="red">This text is red!</font>)`
+ Comments `([coment]: # | [//]: # "Comment" | [//]: # (Comment) | <!-- comment --> )`
+ Admonitions `(> :memo: **Note:** Sunrises are beautiful.)`
+ Image Size `(<img src="image.png" width="200" height="100">)`
+ Image Captions `(<figure><img alt=text=><figcation></figcaption></figure>)`
+ Link Targets `(<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>)`
+ Symbols
+ Table Formatting `(<br>inside cell, <ul><li>inside cell)`
+ Table of Contents(if no suporting heading Ids) `([Underline](#underline))`
+ Videos `([![Image-alt-text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID))`



<br>

### github flavored(ghf)

- collapsed section `(<details> <summary>title</summary></details>)`
- Colors call out `(The background color should be `#ffffff` for light mode and `#0d1117` for dark mode)`










<br><br><br>

# BASIC SYNTAX

### text-formating

\#<sup>^6</sup> headings 6 lvls  
(alt): Alternatively, on the line below the text, add any number of == characters for heading level 1 or -- characters for heading level 2.


(+ extended syntax)
`monospace`

texxt <sub>subscript</sub> text  
text <sup>superscript</sup> text  
`
v2
Subscript H~2~O text  
Superscript X^2^ text   



</br></br>

### quotes
> Text that is a quote




<br><br>

### code-blocks
text `single line-code` text 

```
code-block test
````

>:warning:  
>Escaping Backticks
>If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks >(``).




<br><br>

### Colors call out
The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.




<br><br>

### links
ctrl+k
Link. This site was built using [GitHub Pages](https://pages.github.com/).
You can also use the keyboard shortcut Command+K to [create a link](https://github.com/elmiven/git-chsh/edit/main/chsh.md). When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

*ctrl+v link from text 
You can also create a Markdown hyperlink by **highlighting the text and using Command+V** the keyboard shortcut. 
If you'd like to **replace** the text with the link, use the keyboard shortcut Command+Shift+V.

*Anchor-link
You can link directly to a section in a rendered file by hovering over [the section heading to expose the link](https://github.com/elmiven/md-chsh/edit/main/md-chsh.md#text-formating):

*relative links
GitHub will automatically transform your relative link (or image path) based on whatever branch you're currently on, so that the link or path always works. 
The path of the link will be relative to the current file. 
Links starting with / will be relative to the repository root. You can use all relative link operands, such as ./ and ../.

>(i): Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using >relative links to refer to other files within your repository.


>(i)
>Note: To link to an element on the same page, see linking to heading IDs. To create a link that opens in a new tab or window, see the section on link targets. 

>(i):
>Adding Titles
>You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.
>eg: My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

>(i):
>URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com>


>:warning:
>Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

first part
[hobbit-hole][1]
second part
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle

/!\
Markdown applications don’t agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with %20. Alternatively, if your Markdown application supports HTML, you could use the a HTML tag.



<br><br>

### images
You can display an image by adding ! and wrapping the alt text in [ ]. Then wrap the link for the image in parentheses ().

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)
[(see more info exmpls in docs)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)

*Specifying the theme an image is shown to
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>




<br><br>

### lists (Bullet lists )
*unordered
- George Washington
* John Adams
+ Thomas Jefferson

*ordered
1. James Madison
2. James Monroe
3. John Quincy Adams

*nested
(You can create a nested list by indenting one or more list items below another item.
To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font)
1. First list item
   - First nested list item
     - Second nested list item
 
 
(i)
Starting Unordered List Items With Numbers
use a backslash (\) to escape the period.
 
(i):
Adding Elements in Lists
To add another element in a list while preserving the continuity of the list, indent the element **four spaces or one tab**, as shown in the following examples.
 
 




<br><br>

### HTML
Many Markdown applications allow you to use HTML tags in Markdown-formatted text. This is helpful if you prefer certain HTML tags to Markdown syntax. For example, some people find it easier to use HTML tags for images. Using HTML is also helpful when you need to change the attributes of an element, like specifying the color of text or changing the width of an image.

To use HTML, place the tags in the text of your Markdown-formatted file.

This **word** is bold. This <em>word</em> is italic.

The rendered output looks like this:

This word is bold. This word is italic.

Markdown doesn’t allow you to change the color of text, but if your Markdown processor supports HTML, you can use the <font> HTML tag. The color attribute allows you to specify the font color using a color’s name or the hexadecimal #RRGGBB code.

<font color="red">This text is red!</font>



  
 










# EXTENDED SYNTAX 
  
  
  








<br><br>

### Tasklist
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:


<br><br>
### Mentioning people and teams
@person


<br><br>
### Referencing issues and pull requests
#...


<br><br>
### Referencing external resources


<br><br>
### Using emoji
:+1: :shipit:


<br><br>
### Footnotes
[^1] footnote
[^1]: footnotetext


<br><br>
### Hiding content with comments
<!-- This content will not appear in the rendered Markdown -->


<br><br>
### Ignoring Markdown formatting (escape char \)
Let's rename \*our-new-project\* to \*our-old-project\*.



<br><br>
### Adding a table
You can create tables with pipes | and hyphens -

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |








<br><br>
### horizontal rule (3 or more dashes) 
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.
For compatibility, put blank lines before and after horizontal rules.



<br><br>

### Line Breaks
To create a line break or new line (<br>), end a line with two or more spaces, and then type return.
You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application supports HTML, you can use the <br> HTML tag.

For compatibility, use trailing white space or the <br> HTML tag at the end of the line.



  
<br><br>
  
# HACKS
  
<br>
  
### Underline
Some of these words <ins>will be underlined</ins>.  
  
### Indent (Tab)  
&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.  
  
### Center  
<center>This text is centered.</center>  
<p style="text-align:center">Center this text</p>  
  
### Color  
<font color="red">This text is red!</font>
  
### Comments  
Here's a paragraph that will be visible.
[This is a comment that will be hidden.]: # 
And here's another paragraph that's visible.  
  
### Admonitions
  
>  
> :warning: **Warning:** Do not push the big red button.
>  
  
> :memo: **Note:** ` Sunrises are beautiful. `  
  
> :bulb: ``` **Tip:** Remember to appreciate the little things in life. ```  
  
  
### Image Size
<img src="image.png" width="200" height="100">  
  
### Image Captions 
<figure>
    <img src="/assets/images/albuquerque.jpg"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>
 
![Albuquerque, New Mexico](/assets/images/albuquerque.jpg)
*A single track trail outside of Albuquerque, New Mexico.*

Tip: If your Markdown application supports CSS, you can use CSS to style the appearance of the caption.
    
### Link Targets
<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>
  
### Symbols  

    Copyright (©) — &copy;
    Registered trademark (®) — &reg;
    Trademark (™) — &trade;
    Euro (€) — &euro;
    Left arrow (←) — &larr;
    Up arrow (↑) — &uarr;
    Right arrow (→) — &rarr;
    Down arrow (↓) — &darr;
    Degree (°) — &#176;
    Pi (π) — &#960;

  
  
 ### Table Formatting
  
 Line Breaks Within Table Cells

You can separate paragraphs within a table cell by using one or more <br> HTML tags.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |

  
Lists Within Table Cells

You can add a list within a table cell by using HTML tags.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

  
### Table of Contents

#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

### Videos
[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)
[![Less Than Jake — Scott Farcas Takes It On The Chin](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=PYCxct2e0zI)








# github flavored

<br><br>
### collapsed section
<details>
<summary>CLICK ME</summary>
<p>
#### We can hide anything, even code!

```ruby
   puts "Hello World"
```

</p>
</details>
