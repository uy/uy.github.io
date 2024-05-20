+++
title = 'GoHugo Tutorial'
date = 2024-05-20T22:39:21+03:00
type = "post"
+++

# What is GoHugo
Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again.

If you want to create a static web site like simple portfolio or landing page you can use Hugo.

# Installation
[Official installation steps.](https://gohugo.io/installation/)

### How did I install
I just need to install hugo. Because I already have go.

```bash
brew install hugo
```

# Create your static web site
1. line say hugo to create new site which is named `quickstart`.
2. line move in `quickstart` directory.
3. line initilize of git.
4. line is critic. Because we add our themes with this line.
5. line we say to hugo's config file that we want to use `gokarna` theme.
6. line start to serve static page by hugo.

```bash
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/526avijitgupta/gokarna.git themes/gokarna
echo "theme = 'gokarna'" >> hugo.toml
hugo server
```