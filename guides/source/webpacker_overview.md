**DO NOT READ THIS FILE ON GITHUB, GUIDES ARE PUBLISHED ON https://guides.rubyonrails.org.**

Webpacker Overview
=======================

This guide covers different aspects of the official webpack integration with Rails.
After reading this guide, you will know:

* Understand the basics of bundling assets with webpack

--------------------------------------------------------------------------------

## What Is Webpacker?

Webpacker is the official Rails integration of Webpack. It enables Rails application to bundle 
different kinds of static assets.

INFO. Learn more about Webpack here: https://webpack.js.org/concepts/

## How is Webpacker Different from Sprockets?

WARNING. Be careful, this gives only a rough comparison. Some concepts do not directly map onto each other.

| Sprocket Version                          | Webpacker Version                                                                |
| ----------------------------------------- | -------------------------------------------------------------------------------- |
| `javascript_link_tag`                     | `javascript_pack_tag`                                                            |
| `stylesheet_link_tag`                     | `stylesheet_pack_tag`                                                            |
| `image_url`                               | `image_pack_tag`                                                                 |
| `asset_url`                               | `asset_pack_tag`                                                                 |
| `//= require some_script`                 | `require("some_script")`                                                         |

Maybe list some webpacker only concepts

## Installing Webpacker

* Webpack is default on new projects
* Installing yarn https://yarnpkg.com/getting-started
* Explain rails new with `--webpack=framework`

### Integrating Frameworks with Webpacker

* Explain `package.json`
* Explain rails new with `--webpack=framework`

"Official" Rails integrations at https://www.npmjs.com/search?q=%40rails

List current integrations with a link to their Project pages

```
webpacker:install:angular
webpacker:install:coffee
webpacker:install:elm
webpacker:install:erb
webpacker:install:react
webpacker:install:stimulus
webpacker:install:svelte
webpacker:install:typescript
webpacker:install:vue
```

## Using Webpacker for JavaScript

```
app/javascript
├── channels
│   ├── consumer.js
│   └── index.js
└── packs
    └── application.js
```

### Where to Place Files

### Linking Files 

### Babel and TypeScript

* Explain Transpiler in short

* how to setup typescript

* how to setup babel

* how to setup coffeescript

## Using Webpacker for CSS

* What does PostCSS

## Using Webpacker for Static Assets

## Webpacker in Rails Engines

## Running Webpacker in Development 

## Webpacker in Production

### Deploying Webpacker

### Webpacker and Docker

## Extending and Customizing Webpacker

* Custom Plugin (Maybe a example with ProvidePlugin and jQuery?)

## Troubleshooting Common Problems

## Upgrading Webpacker

## Resources

"Official" Rails integrations at https://www.npmjs.com/search?q=%40rails