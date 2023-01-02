# md cheatsheet 
  [github-md-docs](https://docs.github.com/en/get-started/writing-on-github)


### text-formating

<sub>subscript</sub>

<sup>Superscript</sup>	


### quotes
> Text that is a quote


### code-blocks
`single line-code`

```
code-block test
````


### Colors call out
The background color should be `#ffffff` for light mode and `#0d1117` for dark mode.


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

(i) Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.


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



### lists
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
     - 
