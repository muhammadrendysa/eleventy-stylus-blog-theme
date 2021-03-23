# Eleventy + Stylus Blog theme

A theme repository that contains a blog built with [Eleventy](https://github.com/11ty/eleventy) and [Stylus](https://stylus-lang.com/)

# Features
 - 100% Lighthouse scores
 - Tags as taxonomy
 - Stylus CSS preprocessor
 - Integrated with Eleventy's official [navigation plugin](https://www.11ty.dev/docs/plugins/navigation/)
 - Also generates Atom RSS Feed with Eleventy's official [RSS plugin](https://www.11ty.dev/docs/plugins/rss/)
 - Sitemap generation
 - Non-post pages support (eg. About page, Contact page)
 - Modular type scale implemented in with Stylus

## Demos

TBD

## Screenshot

![website homepage screenshot](screenshot.png?raw=true)

## Prerequisites
[Node.js 12](https://nodejs.org/download/release/latest-v12.x/)

[Yarn](https://yarnpkg.com/) package manager


## Getting started

1. Clone this repo
```
git clone https://github.com/ar363/eleventy-stylus-blog-theme my-blog
```

2. Navigate to the blog directory
```
cd my-blog
```

3. Install dependencies with [yarn](https://yarnpkg.com/)
```
yarn
```
4. Edit `_data/site.js` according to your site preferences

5. Also optionally modify `stylus/abstracts/variables.styl` according to your preference

To watch for changes in Eleventy and Stylus, use `yarn dev`

To build without watching for changes, use `yarn build`