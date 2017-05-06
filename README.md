# O hai

Links:
 * [Running locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) (OSX only because of reasons :/) (skip step 3, then run `bundle exec jekyll serve`)

Lovecraftian markdown fhtagness from [diversen/lovecraft-complete-cthulhu-mythos](https://github.com/diversen/lovecraft-complete-cthulhu-mythos) <3

TODO: clone the theme, add a list of articles in the sidebar (somewhere in the `<header>` in [default.html](https://github.com/pages-themes/dinky/blob/master/_layouts/default.html) I guess)

# Contents
TODO: move this to sidebar.

{% for post in site.pages %}
  [{{post.title}}]({{post.url | remove_first:'/'}})
{% endfor %}

# example stuffs
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/thelifestream/guide-example/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/thelifestream/guide-example/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
