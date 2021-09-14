# Why

I really wanted to play with mkdoc and github action since at work I priarly have to use Confluence
I also found this thing called `mermaid.js` that allow you to make UML diagras and does not need 
some Java backend to generate them (like for example plantuml).

# Description

This repo in an example of simple `React.js` application and `mkdoc` that can keep Markdown
documentation inside directories of React components.

Also I used `mhausenblas/mkdocs-deploy-gh-pages@master` github action to deploy it.

Demo of documentation is present here: https://grayrattus.github.io/mkdocs-gh-action-mermaid-basic.io/

As you can see I included `mermaid.js` from CDN that renders simple UML chart in the browser.
So it does not have to be repeated in every documentation entry.
