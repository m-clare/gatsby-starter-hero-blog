# HeroBlog

A [GatsbyJS](https://www.gatsbyjs.org/) blog starter. <br /><br />

  <br />

![](static/screens/gatsby-starter-hero-blog.gif) <br />

  <br />

## Description

A ready to use, easy to customize 'like theme' starter with a 'Hero' section on the home page.

## Features:

* Easy editable content in **Markdown** files (posts, pages and parts)
* **CSS** with `styled-jsx` and `PostCSS`
* **SEO** (sitemap generation, robot.txt, meta and OpenGraph Tags)
* **Social** sharing (Twitter, Facebook, Google, LinkedIn)
* **Comments** (Facebook)
* **Images** lazy loading and `webp` support (gatsby-image)
* Post **categories** (category based post list)
* Full text **searching** (Algolia)
* **Contact** form (Netlify form handling)
* Form elements and validation with `ant-design`
* **RSS** feed
* 100% **PWA** (manifest.webmanifest, offline support, favicons)
* Google **Analytics**
* App **favicons** generator (node script)
* Easy customizable base **styles** via `theme` object generated from `yaml` file (fonts, colors, sizes)
* React **v.16.3** (gatsby-plugin-react-next)
* **Components** lazy loading (social sharing)
* **ESLint** (google config)
* **Prettier** code styling
* Webpack `BundleAnalyzerPlugin`

## Additional Fork Features:

* Static Jupyter Notebook support

## Prerequisites

If you do not have Gatsby Cli installed yet, do it first.

```text
npm install --global gatsby-cli
```

More information on [GatsbyJS.org](https://www.gatsbyjs.org/tutorial/part-one)

## Getting started

Install the starter using Gatsby Cli `gatsby new` command.

```text
gatsby new [NEW_SITE_DIRECTORY_FOR_YOUR_BLOG] https://github.com/m-clare/gatsby-starter-hero-blog.git
```

Go into the newly created directory and run

```text
gatsby develop
```

to hot-serve your website on http://localhost:8000 or

```text
gatsby build
```

to create static site ready to host (/public).

## Alternate build instructions

If 
```text
gatsby new [NEW_SITE_DIRECTORY_FOR_YOUR_BLOG] https://github.com/m-clare/gatsby-starter-hero-blog.git
```
fails, you can clone the repository and then 

```text
yarn install
```

After dependencies are installed, go to the directory and run as according to the previous instructions.


