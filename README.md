# Lifestyle

[Getting started](#getting-started) |
[Staying up to date with Lifestyle changes](#staying-up-to-date-with-lifestyle-changes) |
[Developer tools](#developer-tools) |
[License](#license)

Lifestyle represents a HTML-first, JavaScript-only-as-needed approach to theme development. It's Shoplazza's first source available theme with performance, flexibility, and acts as a reference for building Shoplazza themes.

* **Web-native in its purest form**: We leverage the latest web browsers to their fullest, while maintaining support for the older ones through progressive enhancement—not polyfills.
* **Lean, fast, and reliable:** Functionality and design defaults to “no” until it meets this requirement. Code ships on quality. Themes must be built with purpose. They shouldn’t support each and every feature in Shoplazza.
* **JavaScript not required, fails gracefully:** We extract every bit of speed and functionality out of HTTP, semantic HTML, and CSS before writing our first line of JavaScript. JavaScript can only be used to progressively enhance features.
* **Server-rendered:** HTML must be rendered by Shoplazza servers using Liquid. Business logic and platform primitives such as translations and money formatting don’t belong on the client. Async and on-demand rendering of parts of the page is OK, but we do it sparingly as a progressive enhancement.
* **Functional, not pixel-perfect:** The Web doesn’t require each page to be rendered pixel-perfect by each browser engine. Using semantic markup, progressive enhancement, and clever design, we ensure that themes remain functional regardless of the browser.


## Getting started

We recommend using Lifestyle as a starting point for theme development. [Learn more on Shoplazza.dev](https://www.shoplazza.dev/docs/create-a-theme?utm_source=github-theme-lifestyle).

> If you're building a theme for the Shoplazza Theme Store, then you can use Lifestyle as a starting point. However, the theme that you submit needs to be [substantively different from Lifestyle](https://www.shoplazza.dev/docs/theme-requirements#2-uniqueness-from-free-shoplazza-themes?utm_source=github-theme-lifestyle) so that it provides added value for merchants. Learn about the [ways that you can use Lifestyle](https://www.shoplazza.dev/docs/lifestyle#ways-to-use-lifestyle?utm_source=github-theme-lifestyle).

## Staying up to date with Lifestyle changes

Say you're building a new theme off Lifestyle but you still want to be able to pull in the latest changes, you can add a remote `upstream` pointing to this Lifestyle repository.

1. Navigate to your local theme folder.
2. Verify the list of remotes and validate that you have both an `origin` and `upstream`:
```sh
git remote -v
```
3. If you don't see an `upstream`, you can add one that points to Shoplazza's Lifestyle repository:
```sh
git remote add upstream https://github.com/Shoplazza/lifestyle.git
```
4. Pull in the latest Lifestyle changes into your repository:
```sh
git fetch upstream
git pull upstream main
```

## Developer tools

There are a number of really useful tools that the Shoplazza Themes team uses during development. Lifestyle is already set up to work with these tools.

### Shoplazza CLI

[Shoplazza CLI](https://github.com/Shoplazza/shoplazza-cli) helps you build Shoplazza themes faster and is used to automate and enhance your local development workflow. It comes bundled with a suite of commands for developing Shoplazza themes—everything from working with themes on a Shoplazza store (e.g. creating, publishing, deleting themes).

You can follow this [quick start guide for theme developers](https://www.shoplazza.dev/docs/shoplazza-cli-overview?utm_source=github-theme-lifestyle) to get started.


## Theme Store submission

The [Shoplazza Theme Store](https://themes.shoplazza.com?utm_source=github-theme-lifestyle) is the place where Shoplazza merchants find the themes that they'll use to showcase and support their business. As a theme partner, you can create themes for the Shoplazza Theme Store and reach an international audience of an ever-growing number of entrepreneurs.

You can follow this [quick start guide for theme developers](https://www.shoplazza.dev/docs/shoplazza-cli-overview?utm_source=github-theme-lifestyle) to get started.
Ensure that you follow the list of [theme store requirements](https://www.shoplazza.dev/docs/theme-requirements?utm_source=github-theme-lifestyle) if you're interested in becoming a [Shoplazza Theme Partner](https://www.shoplazza.dev/docs/theme-store-overview?utm_source=github-theme-lifestyle) and building themes for the Shoplazza platform.

## License
Copyright (c) 2021-present Shoplazza. See [LICENSE](./LICENSE.md) for further details.
