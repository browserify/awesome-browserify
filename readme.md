<div align="center"><img src="browserify.png" alt="Browserify!"></div>

# Awesome Browserify [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> :crystal_ball: A curated list of awesome [Browserify](https://github.com/substack/node-browserify) resources, libraries, and tools.

Work in progress! Please help improve this list by [contributing](contributing.md)!

### Contents

- [About](#about)
- [Official Resources](#official-resources)
- [Tutorials](#tutorials)
- [Demos](#demos)
- [Development Tools](#development-tools)
  - [Servers](#servers)
  - [Plugins](#plugins)
  - [Watchers](#watchers)
  - [CSS Bundlers](#css-bundlers)
  - [Transforms](#transforms)
  - [Node in the Browser](#node-in-the-browser)
- [Production Tools](#production-tools)

## About

Browserify lets you `require('modules')` in the browser by bundling up all of your dependencies.

You can use a node-style `require()` to organize your browser code and load modules installed by npm. Browserify will recursively analyze all the `require()` calls in your app in order to build a bundle you can serve up to the browser in a single `<script>` tag.

## Official Resources

- [Docs](https://github.com/substack/node-browserify#usage)
- [Handbook](https://github.com/substack/browserify-handbook)
- [Repo](https://github.com/substack/node-browserify)
- [Website](http://browserify.org/)

## Tutorials

- [Hello World with Browserify](http://browserify.org/#middle-section)
- [Introduction to Browserify](http://superbigtree.tumblr.com/post/54873453939/introduction-to-browserify)
- [Using npm on the client side](http://dontkry.com/posts/code/using-npm-on-the-client-side.html)

This is a stub! Please [help fill it out](https://github.com/ungoldman/awesome-browserify/edit/master/readme.md).

## Articles

- [How Browserify Works](http://benclinkinbeard.com/posts/how-browserify-works/)

This is a stub! Please [help fill it out](https://github.com/ungoldman/awesome-browserify/edit/master/readme.md).

## Demos

This is a stub! Please [help fill it out](https://github.com/ungoldman/awesome-browserify/edit/master/readme.md).

## Development Tools

### Servers

- [budo](https://github.com/mattdesl/budo) - A dev server for rapid prototyping.
- [beefy](https://github.com/chrisdickinson/beefy) - Local development server that aims to make using browserify fast and fun.
- [wzrd](https://github.com/maxogden/wzrd) - Super minimal browserify development server.

### Plugins

- [browserify-hmr](https://github.com/AgentME/browserify-hmr) - Hot Module Replacement plugin for Browserify.

### Watchers

- [watchify](https://github.com/substack/watchify) - Watch mode for browserify builds.
- [persistify](https://github.com/royriojas/persistify) - A wrapper around `browserify` to make incremental builds.

### CSS bundlers

- [sheetify](https://github.com/stackcss/sheetify) - Modular CSS bundler for browserify.
- [parcelify](https://github.com/rotundasoftware/parcelify) - Add css to your npm modules consumed with browserify.
- [css-modulesify](https://github.com/css-modules/css-modulesify) - A browserify plugin to load CSS Modules.

### Transforms

- [babelify](https://github.com/babel/babelify) - Browserify transform for babel.
- [aliasify](https://github.com/benbria/aliasify) - Remap require calls at build time.
- [brfs](https://github.com/substack/brfs) - `fs.readFileSync()` and `fs.readFile()` static asset browserify transform.

### Node in the Browser

- [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - A port of node's `crypto` module to the browser.
- [stream-browserify](https://github.com/substack/stream-browserify) - The `stream` module from node core, for browsers!
- [buffer](https://github.com/feross/buffer) - The `buffer` module from node.js, for the browser.

## Production Tools

- [wzrd.in](https://wzrd.in/) - Browserify CDN. Browserify-as-a-Service!
- [bankai](https://github.com/yoshuawuyts/bankai) - DIY asset server. Serves HTML, CSS and JS as streams.

## Contributing

Contributions welcome! Please read the [contributing guidelines](contributing.md) before getting started.

## License

The [browserify logo](browserify.png) is by [substack](https://github.com/substack).

All other content is released to the public domain under [CC0-1.0](https://spdx.org/licenses/CC0-1.0.html).

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
