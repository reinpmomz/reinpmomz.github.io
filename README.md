
# Make your website with R Markdown in minutes

This is a template (and tutorial) for creating your website with R Markdown in minutes.

The official document from RStudio can be found [here](http://rmarkdown.rstudio.com/rmarkdown_websites.html).

## Procedure

### Prerequisites

- Make sure that you have the latest versions of R, RStudio and package rmarkdown. I had problems of encoding because of that. 

- Make sure that you have enabled Git in RStudio. More information can be found [there](https://privefl.github.io/advr38book/good-practices.html#git).

- You need a GitHub account.

### Make the first version of your website

- Fork this repo (top-right) and rename it to be 'YOURGITHUB.github.io' (in Settings of your brand new repo).

- Get the link from cloning the repo. Use the green button "Clone" and make sure you use SSH, not HTTPS. Then, go to RStudio, create a New Project > Version Control > Git and copy this link. You have cloned your new repo as an R project.

- Build the website by running `rmarkdown::render_site(encoding = "UTF-8")` or just `Ctrl/Cmd + Shift + B`.

- Commit and push everything from RStudio.

- Go see your new website at https://YOURGITHUB.github.io/index.html.

### Change the content of your website

- Modify `_site.yml`, `index.Rmd`, `about.Rmd`, `cv.Rmd` and `CV.pdf` with your own content. 
- Build your website again. At any moment, you can preview your website locally, by rendering your site and viewing any of your local html file in your Web Browser. 

- Commit and push everything from RStudio.

- Go see your new website with your own content at https://YOURGITHUB.github.io/.


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/reinpmomz/reinpmomz.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/reinpmomz/reinpmomz.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

