### Github Pages
Get a brief introduction of how to build your own [Github Pages](https://pages.github.com).

### My Pages
https://archidemi.github.io/index.html

The site is still under construction...

### Construction Stages
The site is built by utilizing RStudio and the `rmarkdown` package.
+ `_site.yml`: layout the blueprint of the site.
+ `index.Rmd`: the homepage of the site.
+ `about.Rmd`: something about the site.
+ `projects.Rmd`: a page to list the projects with links and descriptions.
+ `build_site.R`: the code to render the other `.html` files to build the site.
```R
# setting the working directory is necessary
setwd('~/yourfolder')

rmarkdown::render_site
```
+ `site_libs` is a folder generated after rendering, including css styles and themes supported by `rmarkdown`

### Resources
https://rmarkdown.rstudio.com/rmarkdown_websites.html
