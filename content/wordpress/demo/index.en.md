---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: af15b37e8ed932b0

---

-   setup (on the WordPress side, in .Renviron) was discussed on the slides, see [goodpress setup vignette](https://maelle.github.io/goodpress/articles/setup.html)

-   install the remotes package, [`install.packages("remotes")`](https://rdrr.io/r/utils/install.packages.html)

-   install the goodpress package, [`remotes::install_github("maelle/goodpress", ref = "main")`](https://remotes.r-lib.org/reference/install_github.html)

-   create a folder, possibly a subfolder in a folder called "my-wordpress-posts" or so, "2020-07-03-cool-post".

-   in that folder, create index.Rmd.

-   in index.Rmd, paste [example content](/snippets/#goodpress-post). look at the YAML field, see also [goodpress usage vignette](https://maelle.github.io/goodpress/articles/goodpress.html)

-   knit.

-   use [`goodpress::wp_post("2020-07-03-cool-post")`](https://maelle.github.io/goodpress//reference/wp_post.html)

