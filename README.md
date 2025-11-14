ACTIF CEA Website
====================
ACTIF CEA Website is based on the template [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# How to use

### Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

To create a post, create a file in the director '/_posts' with name yyyy-mm-dd-post-title.markdown

Copy this content
```
---
title: Title of you post
subtitle: Subtitle of the post
layout: default
modal-id: 987 # must be unique
date: 2022-01-01 # date of writing
img: colloque-agir-thumbnail.jpg # name of the image stored in /img/portfolio
thumbnail: colloque-agir-thumbnail.jpg # name of the image stored in /img/portfolio 400x289
alt: image-alt 
project-date: 2022-01-01 # Date of the project used to sort future and past events
date-label: 01-01-2022 # Date displayed on the event
location: Location of event
category: Category of event
---

--> Here your can write anything you want ! even html content !
```

### Publish modifications

Once you are done with your modifications, simply push them (commit+push). Github will automatically refresh the website based on the modifications in a few seconds/minutes.

# Website link

https://actif-cea.github.io/

=========
For more details, read [documentation](http://jekyllrb.com/)
