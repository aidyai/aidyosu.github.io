## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/aidyosu/aidyosu.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/aidyosu/aidyosu.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

# Site settings
title: Klise Theme # site title
description: >- # site description
  He's writing in Bahasa about web technology and experience as a journal 
  for documentation things that he learned, meet him <a href="https://github.com/piharpi" target="_blank" rel="noopener">@github</a>.
lang: en-US # default lang
timezone: Asia/Jakarta # set your timezone
image: assets/img/ogp.png # This image used for Open Graph more info https://ogp.me/
repo: https://github.com/piharpi/jekyll-klise # site repo [optional]
mode: dark # default theme "dark" | "light"

# Profile settings
author:
  name: Jekyll Klisé # author name
  bio: >- # tell to the world
    The minimalist Jekyll theme, light and dark mode support, for running a personal site and blog, 
    meet Klisé theme at <a href="https://github.com/piharpi/jekyll-klise" target="_blank" rel="noopener">@github</a>.
  username: username # general username
  github: github_username # github username
  twitter: twitter_username # twitter username
  facebook: facebook_username # facebook username
  email: your-email@email.com # email adress
  avatar: /assets/img/avatar.jpg # change with your own avatar

# URL settings
url: "https://klise.now.sh" #
baseurl:
permalink: /:title/
google_analytics: # leave it blank if not wish
fb_appid:

# Collection setting
collections:
  posts:
    output: true

# Markdown settings
markdown: kramdown
highlighter: rouge
kramdown:
  syntax_highlighter: rouge

# Default front matter
defaults:
  - scope:
      path: ""
    values:
      layout: post
      comments: false

# Jekyll Compose default front matter
jekyll_compose:
  post_default_front_matter:
    modified:
    tags: []
    description:
  draft_default_front_matter:
    modified:
    tags: []
    description:

# Homepage limit posts
number_of_posts: 5

# Build settings
# theme: klise
sass:
  style: compressed

include:
  - _redirects
  - .htaccess

exclude:
  - CNAME
  - Gemfile
  - Gemfile.lock
  - LICENSE
  - CHANGELOG.md
  - README.md
  - node_modules
  - CODE_OF_CONDUCT.md
  - CONTRIBUTING.md
  - lighthouse.png
  - klise-*.gem
  - klise.gemspec

# Plugins
plugins:
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-postfiles





### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
