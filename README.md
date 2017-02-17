# CS10
Site for CS10

The handouts are written in markdown and the static
site is generated by a Python program called MkDocs.

The YAML configuration file (`mkdocs.yml`) describes the 
structure of the generated site and mkdocs uses the 
markdown files in the `docs` folder as a source of the 
site content.

Go to the [MkDocs documentation](http://www.mkdocs.org/) for mkdoc install instructions.

Build
-----
Clone the repo:
```sh
git clone https://github.com/cs-si-ucr/cs10.git
```

Host the site locally at localhost:8000
```sh
mkdocs serve
```

Deploy the site to http://cs-si-ucr.github.io/cs10/
```sh
mkdocs gh-deploy
```

Cool Resources
--------------
[Markdown reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


Relative Link Test
---

[style](./style.md)

