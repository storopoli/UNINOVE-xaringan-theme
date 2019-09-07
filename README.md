# UNINOVE `CSS` Theme

This a `CSS`  theme of [UNINOVE - Universidade Nove de Julho](www.uninove.br) to be used with [`xaringan`](https://github.com/yihui/xaringan) slides in [`Rmarkdown`](https://rmarkdown.rstudio.com)

## Resources

* [UNINOVE High-res Logo](resources/UNINOVE_LOGO.JPG)
* [UNINOVE CSS file](resources/uninove.css)

### How to deploy

1. Put the `uninove.css` file in the same directory as your `.Rmd` slides file

2. Customize the YAML section

1. ```yaml
   output:
     xaringan::moon_reader:
       css: ["default", "uninove.css", "default-fonts"]
       lib_dir: libs
       nature:
         beforeInit: "macros.js"
         highlightStyle: github
         highlightLines: true
         countIncrementalSlides: false
   ```

### UNINOVE Colours

* Blue: `#29427A`
* Red: `#DF402B`
* White: `#FFFFFF`