# candy

A minimalist Hugo theme focused on readability and simplicity. It is currently powering [hugomartins.io](https://www.hugomartins.io).

## Requirements

- Hugo v0.59

## Features

- Great readability with [Alegreya](https://fonts.google.com/specimen/Alegreya) and [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
- Code highlighting via `pygments`, with some customization.
- Responsive, works on smaller screens.
- Integration with Plausible Analytics.

## Installation

```
$ cd themes/
$ git clone https://github.com/caramelomartins/candy.git
```

You can find an example `config.yaml` inside `exampleSite`.

## Content

### Static

You can use static pages at the root of `content/`. If you wish to create a small introduction on the homepage, you can use `_index.md` at the root of `content/`. As per Hugo's templating order, it will be loaded as the body content for the root of the website.

## Dynamic

### Essays

`essays` are the default dynamic content, representing articles, blog posts, etc. You can add a `_index.md` to add a custom introduction to the list of essays page, similar to the homepage. These have specific layouts applied to them.

### Other

You should be able to add more dynamic content under different archetypes and folders, the theme will collect that content and create default single and list pages for that content.

## Archetypes

Currently there's two archetypes:

- `default.md`, which will be used for any page other than an essay;
- `essay`, which will be used for essays that appear in the homepage.

## License

[MIT](https://github.com/caramelomartins/candy/blob/master/LICENSE)