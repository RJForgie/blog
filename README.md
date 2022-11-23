
[![pages-build-deployment](https://github.com/RJForgie/rjforgie.github.io/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/RJForgie/rjforgie.github.io/actions/workflows/pages/pages-build-deployment)


# Software engineering blog.

The aim of this site is to learn in public, share thoughts on building software and document the journey to [become a wizard](https://jvns.ca/blog/so-you-want-to-be-a-wizard/).


## Run Locally
Install the version of Ruby shown in the `.ruby-version` file. I would recommend using [rbenv](https://github.com/rbenv/rbenv) to manage your installed Ruby versions

Clone the project

```bash
  git clone https://github.com/RJForgie/rjforgie.github.io.git
```

Go to the project directory

```bash
  cd rjforgie.github.io
```

Install dependencies

```bash
  bundle install
```

Start the server

```bash
  bundle exec jekyll serve
```


## Deployment

This project is deployed to [Github Pages](https://pages.github.com/) via Github Actions.

## Acknowledgements

Theme based on [Sidey from Ronv](https://github.com/ronv/sidey)
