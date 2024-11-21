---
title: "About the Website"
layout: textlay
excerpt: "About the website."
sitemap: false
permalink: /aboutwebsite.html
---

# About This Website

This website was developed using a template provided by the [Allan Lab](https://github.com/allanlab/allanlab) and is powered by [Jekyll](https://jekyllrb.com), with design elements from [Bootstrap](http://www.getbootstrap.com) and [Bootswatch](http://www.bootswatch.com). The goal is to offer a straightforward and flexible template for academic research groups to present their work and manage updates easily.

### Getting Started

The website structure is designed for easy editing and updates:
- **Markdown Pages**: Content pages use [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for simple formatting.
- **Data-Driven Sections**: Information such as publications, news, and team members is stored in `.yml` data sheets in the `_data` folder, making it easy to update without editing individual HTML files.
- **Jekyll Processing**: Jekyll takes all markdown and data files and generates HTML files in the `_site` folder for publishing.

If you’re new to Jekyll, we recommend reviewing the [Wikipedia article](https://en.wikipedia.org/wiki/Jekyll_(software)) or Jekyll’s official [website](https://jekyllrb.com) for an introduction.

### Forking and Publishing on GitHub

To use this template, create a GitHub account and follow these steps:

1. **Fork the Repository**: Visit [the Allan Lab GitHub repository](https://github.com/allanlab/allanlab), then click "Fork" to create a copy.
2. **Rename the Repository**: Change the repository name to `"your_username.github.io"`.
3. **Publish**: After renaming, GitHub automatically publishes your website at *https://your_username.github.io/*.
4. **Edit Directly on GitHub**: You can edit files directly on GitHub or install Jekyll locally to make and preview changes on your computer.

For local editing, refer to these [setup instructions](https://www.taniarascia.com/make-a-static-website-with-jekyll/) and [tutorials](https://scotch.io/tutorials/getting-started-with-jekyll-plus-a-free-bootstrap-3-starter-theme).

### Customizing Your Website

Make the website your own by following these customization steps:

1. **Update Data Files**:
   - Go to the `_data` folder and edit `news.yml`, `publist.yml`, and `team.yml` to add your own information.
   - **Formatting Tip**: Jekyll requires strict YAML formatting, so avoid extra spaces or tabs.
2. **Modify Pages**:
   - Edit content files in the `_pages` folder. The homepage can be customized in `homelay.html` within `_layouts`.
3. **Styling**:
   - Minor style changes can be made in `main.sass` (within `CSS`), or you can adjust the Bootstrap theme in `_variables.sass`.
   - You may also replace the theme with your own CSS in the `_sass` directory.

### Acknowledgments and Copyright

Feel free to use and adapt this template as needed. **Credit to the Allan Lab** for creating the original version of this website template. If you’d like, share your modified website with us, and we may include it in a showcase.

Comments and suggestions are always welcome!
