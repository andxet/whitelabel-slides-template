# WhiteLabel slides template


## Installation

### With `git clone`

```bash
$ git clone my-slides git@github.com:fabe/gatsby-starter-deck.git
$ cd my-slides
$ yarn
```

## Usage

Create a new floder named after your presentation's name  inside the `src/slides` floder.

Create a markdown file e.g. `src/slides/name-of-your-presentation/01.md`

```bash
# To develop & write
$ yarn develop

# To build
$ yarn build
```

**Remember**: Create a new branch from **develop**. Branch's name must follow this naming convention: **presentations/name-of-your-presentation**

## Writing

By default, use [src/slides/](src/slides/).

Markdown files are loaded in sorted path order. Slides are generated by
splitting each markdown file along `<hr/>` elements (`---` in Markdown lingo).

Examples:

```md
# This is the first slide

---

## This is the second slide

![Monkey](//i.imgur.com/PnbINJ6.gif)
```

You can also use HTML inside slides, also Bootsrap is included in the project.

## Deploy

When you are ready to deploy your slides you can create a [Pull Request](https://github.com/WhiteLabelCommunity/whitelabel-slides-template/pulls) to **master**, it will automatically create a deploy preview on Netlify. You can see the url in the pull request page

