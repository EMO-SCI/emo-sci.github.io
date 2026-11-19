Agency Jekyll theme
====================

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)

# How to use

### Portfolio

Papers are stored in `/_posts` using the `<year>-<month>-<day>-<paper>-<conference>.markdown` naming convention (for example, `2022-10-17-scitweets-cikm.markdown`). Each paper file should include `title`, `paper_url`, `published`, and `conference` in its front matter.

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'


# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)

# Run local

```shell
docker build --no-cache -t web .
docker run -d --name web -p 4000:4000 -p 35729:35729 -v "$PWD":/site web
```