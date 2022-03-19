# Welcome to HeadFirst's blog


## Blog 1
  -Learning Objectives:\
    1. Learn Destructuring in JavaScript\
    2. Learn how markdown works
    
  Learned a lot about destructuring in JS and how effective it is. Also learned about using the ... (spread operator) which is very helpful in dealing with various arrays and forming new arrays from elements in a previous array. I also learned about how to use destructuring in objects, and how to set default values and their use case.
  
  -Challenges
  1. Ran into a bug regarding destructuring in Objects and mutating the variables, where my code would result into an error.
  How I overcame this problem:
  ```
  // Mutating variables
let a = 111;
let b = 999;
let obj= {a:23,b: 7, c:14};

({a, b} = obj); // whenever you start with curly brackets, javascript expects a code block, therefore you must wrap the entire code line with curly braces () for it to read properly
console.log(a,b); // outputs 23, 7
  ```
  
  
    
You can use the [editor on GitHub](https://github.com/GHeadFirst/HeadFirstblog/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/GHeadFirst/HeadFirstblog/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
