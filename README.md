---
title: "About me"
permalink: "/about me/"
layout: page
---

## Installation
Just fork this [repository](https://github.com/niklasbuschmann/contrast) and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.


## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Site Title"
author: "Charles Onamudiana Okoruwa"
description: "My personal site about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```


# Charles Okoruwa Onamudiana
* I love God.
* I love swimming and reading. Swimming helps me relax.
* I love partying. This helps me get off things from my head!
## Technical Background
- I studied Computer science in my undergraduates program. FORTRAN was my first programming language, i did a little bit of C++ and java. I completed the HTML and CSS course on [SOLOLEARN.](sololearn.com) I am currently doing Python Now in my master's program.

![My favorite Meme](https://images7.memedroid.com/images/UPLOADED729/5ced9b82177ca.jpeg)
