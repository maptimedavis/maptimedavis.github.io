How to Edit
============================================

The structure of this site is a little different than you might expect. What looks like pages on this site are actually popups (modals) rather than stand-alone html pages. These are stored in the `_posts` folder. The date in the file name creates the ordering on the home page. Do not rename the files.

The files contain a header wrapped in `---`. The `img` section is where you change the image. Do not change the date.

Below the header, edit the page using HTML. W3Schools has an excellent [HTML Reference and Tutorial](https://www.w3schools.com/html/default.asp).


#Freelancer Jekyll theme information:

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/)

The templating language this theme uses is called [Liquid](https://shopify.github.io/liquid/)

## How to use
 - Place a image in `/img/portfolio/`
 - Replace `your-email@domain.com` in `_config.yml` with your email address. Refer to [formspree](http://formspree.io/) for more information.
 - Create posts to display your projects. Use the follow as an example:
```txt
---
layout: default
modal-id: 1
date: 2020-01-18
img: cabin.png
alt: image-alt
project-date: January 2020
client: The Client
category: Web Development
description: The description of the project

---
```

## Demo
View this jekyll theme in action [here](https://jeromelachaud.com/freelancer-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/jeromelachaud/freelancer-theme/master/screenshot.png)

---------
For more details, read the [documentation](http://jekyllrb.com/)
