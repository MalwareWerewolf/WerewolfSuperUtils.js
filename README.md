This repo contains some utilities written in Javascript for [Hugo](https://github.com/gohugoio/hugo).

Simply copy these files into your `static` folder and link them in your config.

## remove-disqus-ads.js

This script is currently working with the latest Disqus version, if it finds an iframe tag which contains ads inside the disqus_thread, it removes it. 

Depending how Disqus will be updated, this script will need to be updated as well in order to hide the ads on the website.

## center-images.js

Center all the `<img>` tags generated with the Markdown syntax.

## hugo-coder-center-headings.js

Center all the headings and add under the post's title a `<hr>` tag to separate it from the main content. This script can work with other themes, but it mainly works with [hugo-coder](https://github.com/luizdepra/hugo-coder) and it also requires some SCSS code to adjust some headings on the mobile. You can find the SCSS code in this repo under `../SCSS/hugo-coder-center-headings.scss`. Copy the file into your `assets` folder and link it in the config.