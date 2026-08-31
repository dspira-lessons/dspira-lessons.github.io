# Contributing

## Local Development

Follow these steps to work on the website and view a preview locally.

Clone the repository:

```sh
git clone https://github.com/dspira-lessons/dspira-lessons.github.io/
cd dspira-lessons.github.io
```

Configure a virtual environment:

```sh
bundler config set --local path 'vendor'
```

Install dependencies and serve. Ensure you have Ruby headers installed (the `ruby-dev` package on Debian).

```sh
bundle install
bundle exec jekyll serve
```

Pass `--watch` to the latter command if you want live reloads.

The web server will run at http://localhost:4000

## Adding a New Post

[New Post](https://dspira-lessons.github.io/newpost/)

## LLM Policy

No usage of Large Language Models (LLMs) or other Generative "AI" is permitted when contributing to this project.
