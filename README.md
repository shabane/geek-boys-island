# a deploy ready site for creating persian book

whenever you need a to create a persion book, simple just use this repo. it's configured and deploy ready with hugo-book theme

## installation
to use this you should firest install hugo

```bash
snap install hugo --channel=extended
```

then clone the repo

```bash
git clone --depth 1 --recurse-submodules https://github.com/shabane/geek-boys-island.git
```


## deploy

to deploy just fork this repo and edit the *config.toml* file with
your *github pages url*

```toml
 baseURL: https://yourUserName.github.io/
```


## working with

to add chapter and other book in your single book, just read [this](https://shabane.github.io/geek-boys-island/)
