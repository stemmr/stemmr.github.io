### Arthur's Jupyter Books
This is the repo for the Jupyter Book published at stemmer.github.io! The structure of this repo is the following:

1. Book source on `main` branch under `/book`
2. Built book on `gh-pages` branch

### Building the Book

On the root of the repo run
```
jupyter-book build book
ghp-import -n -p -f book/_build/html
```

### Adding a new Page

refer to the documentation on the Jupyter Book website: https://jupyterbook.org/en/stable/start/new-file.html

1. Create new 