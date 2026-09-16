# Soul Hatch Website

This repository contains the code behind <https://soulhatch.band/>

## Technology Stack

Though not conventional, this website utilizes [pug](https://www.npmjs.com/package/pug) as a static website builder. I wanted a static website so it could be hosted for free and highly available on Github Pages, or cheaply on S3 if too much traffic is generated (in my dreams!)

I surveyed a couple static site generators like Hugo and Jekyll, but they felt too opinionated to me. I wanted the templating features of a static site generator, while still being able to custom write all the HTML, CSS, JS, so I could design exactly the site I wanted for my bands. After all, music is an art, so I think a band's website should be art too.

So I decided to use PugJS, for a few reasons:

- HTML is such an ugly language, sorry not sorry
- I can utilize [includes](https://pugjs.org/language/includes.html) and [inheritance](https://pugjs.org/language/inheritance.html) to build templates, so I don't have to rebuild common elements for each page.
- You can utilize pugcli to pre-render .pug files into minified html

## Deploy Process
