---
# An instance of the About widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: about

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

#title: About me

# Edit the below buttons in /layouts/partials/widgets/about.html

cta:
    label: '**More about me**'
    url: '/more_about_me/'
    icon_pack: fa
    icon: file-pdf

cta_alt:
  label: '**More about me**'
  url: 'add link to page'
#  icon_pack: fa
#  icon: file-pdf

design:
  columns: "1"  
  background:
    image: garden_math.jpg
    image_darken: 0.25
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["7px", "45px", "1px", "0"]

# Choose the user profile to display
# This should be the username (folder name) of a profile in your `content/authors/` folder.
# See https://wowchemy.com/docs/get-started/#introduce-yourself
author: admin
---