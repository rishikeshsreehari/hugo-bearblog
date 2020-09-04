# Hugo Bear Blog ![Test](https://github.com/janraasch/hugo-bearblog/workflows/CI/badge.svg?branch=master&event=push)

🧸 A [Hugo](https://gohugo.io/)-theme based on [Bear Blog](https://bearblog.dev).

> Free, no-nonsense, super-fast blogging.

## Demo

For a current & working demo of this theme, please check out https://janraasch.github.io/hugo-bearblog/ 🎯.

## Installation

If you already have a Hugo site on your machine, you can simply add this theme via

```
git submodule add https://github.com/janraasch/hugo-bearblog.git themes/hugo-bearblog
```

Then, adjust the `config.toml` as detailed below.

For more information, read the official [setup guide][hugo-setup-guide] of Hugo.

## Adjust configuration / config.toml

Please check out the [config.toml](https://github.com/janraasch/hugo-bearblog/blob/master/exampleSite/config.toml) included in the [exampleSite](https://github.com/janraasch/hugo-bearblog/tree/master/exampleSite) of this theme.

## Content & structure

### Starting fresh

If you are starting fresh, simply copy over the contents of the `exampleSite`-directory included in this theme to your source directory. That should give you a good idea about how things work, and then you can go on from there to make the site your own.

### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.

#### Page

You can add **a new page** via running

```
hugo new my-new-page.md
```

#### Blog-Post

You can add **a new blog-post** via running

```
hugo new blog/my-new-post.md
```

### Adding your branding / colors / css

Add a `custom_head.html`-file to your `layouts/partials`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`style.html`](https://github.com/janraasch/hugo-bearblog/blob/master/layouts/partials/style.html)-file to find our which CSS-styles are applied by default.

## Issues / Feedback / Contributing
Please use [GitHub issues](https://github.com/janraasch/hugo-bearblog/issues) and [Pull Requests](https://github.com/janraasch/hugo-bearblog/pulls).

If you do not have a GitHub-account, please hit me up via e-mail (see [janraasch.com](https://www.janraasch.com)).


## Sponsor [![Pay me][insert-coins-svg]][paypal-dot-me]
Please consider supporting my work via [GitHub Sponsors][github-sponsors] or [PayPal][paypal-dot-me].

[![GitHub Stats](https://github-readme-stats.vercel.app/api/?username=janraasch)][github-sponsors]

## Special Thanks 🎁

A special thank you goes out to [Herman](https://herman.bearblog.dev), for creating the original [ʕ•ᴥ•ʔ Bear Blog](https://bearblog.dev/).

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License) © [Jan Raasch](https://www.janraasch.com)

[paypal-dot-me]: https://www.paypal.me/janraasch/7,00
[github-sponsors]: https://github.com/sponsors/janraasch
[insert-coins-svg]: https://img.shields.io/badge/insert-coins-11dde2.svg
[hugo-setup-guide]: https://gohugo.io/getting-started/installing
