# Awesome WebExtensions with stars

> A curated list of awesome resources for WebExtensions development.

WebExtensions are a cross-browser system for developing browser add-ons. To a large extent the system is compatible with the extension API supported by Google Chrome. Extensions written for this browser will in most cases run in Firefox with just [a few changes](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Porting_a_Google_Chrome_extension).

Follow [@fregante](https://fregante.com) for more webext-related news.

## Contents

* [Getting started](#getting-started)
* [Community](#community)
* [Libraries and Frameworks](#libraries-and-frameworks)
* [Tools](#tools)
* [Testing](#testing)
* [Boilerplates](#boilerplates)
* [Sample Extensions](#sample-extensions)

## Getting started

* [Chrome Extensions documentation](https://developer.chrome.com/docs/extensions/reference) - Documentation for the original Chrome extension model.
* [Mozilla's WebExtensions documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions) - MDN wiki for the WebExtensions API.
* [Browser support for WebExtensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Browser_support_for_JavaScript_APIs) - Compatibility table for Chrome, Edge, Firefox, and Opera.
* [Safari Extensions documentation](https://developer.apple.com/safari/extensions/) - Developer documentation on building Safari extensions. Technically not WebExtensions, the API is completely different.
* [Opera API support](https://dev.opera.com/extensions/apis/) - Detailed WebExtensions support for Opera.
* [Browser Extension Standard](https://browserext.github.io/browserext/) - Standard for the API, supported by Mozilla, Opera and Microsoft.

## Community

* [Google Groups](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-extensions) - Discussions.
* [Mozilla Discourse](https://discourse.mozilla.org/c/add-ons) - Discussions.
* [`#addons:mozilla.org`](https://matrix.to/#/#addons:mozilla.org) - Matrix channel by Mozilla.
* [`google-chrome-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/google-chrome-extension) - Relevant questions.
* [`firefox-addon-webextensions` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/firefox-addon-webextensions) - Relevant questions.
* [`microsoft-edge-extension` tag on Stack Overflow](https://stackoverflow.com/questions/tagged/microsoft-edge-extension) - Relevant questions.

## Libraries and Frameworks

Code meant become part of the extension.

* [mozilla/webextension-polyfill](https://github.com/mozilla/webextension-polyfill) ⚠️ Archived - Polyfill to support the standardized promise based API in the `browser` namespace.
* [ExtPay](https://github.com/Glench/ExtPay) ⭐ 761 | 🐛 11 | 🌐 JavaScript | 📅 2026-07-18 - Take secure payments in extensions without needing to run a server backend.
* [webext-options-sync](https://github.com/fregante/webext-options-sync) ⭐ 157 | 🐛 1 | 🌐 TypeScript | 📅 2024-11-17 - Helps you manage and autosave your extension's options.
* [More…](https://github.com/fregante/webext-fun) ⭐ 138 | 🐛 0 | 📅 2025-03-16
* [redux-webext](https://github.com/ivantsov/redux-webext) ⭐ 108 | 🐛 13 | 🌐 JavaScript | 📅 2022-06-23 - Uses Redux for managing the state of your WebExtension.
* [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) ⭐ 92 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-11 - Automatically inject your `content_scripts` on custom domains.
* [webext-storage-cache](https://github.com/fregante/webext-storage-cache) ⭐ 83 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-05 - Map-like promised cache storage with expiration.
* [inject-react-anywhere](https://github.com/OlegWock/inject-react-anywhere) ⭐ 59 | 🐛 1 | 🌐 TypeScript | 📅 2024-10-22 - Inject React components into 3rd party sites with convenient API and styles isolation.
* [@types/firefox-webext-browser](https://www.npmjs.com/package/@types/firefox-webext-browser) - Supplies TypeScript types for the `browser` namespace.

## Tools

Apps that help you manage your extensions.

* [Extension.js](https://github.com/cezaraugusto/extension.js) ⭐ 5,067 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-21 - Plug-and-play, zero-config, cross-browser extension development tool.
* [mozilla/web-ext](https://github.com/mozilla/web-ext) ⭐ 3,128 | 🐛 226 | 🌐 JavaScript | 📅 2026-08-21 - Command line tool to help build, run, and test WebExtensions.
* [Chrome extension source viewer](https://github.com/Rob--W/crxviewer) ⭐ 1,713 | 🐛 26 | 🌐 JavaScript | 📅 2026-06-21 - WebExtension to view source code of extensions directly on the store.
* [Chrome Webstore Upload](https://github.com/fregante/chrome-webstore-upload-cli) ⭐ 503 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-28 - Upload the extension to the Chrome Web Store via cli (or on GitHub Actions, automatically).
* [webpack-extension-reloader](https://github.com/rubenspgcavalcante/webpack-extension-reloader) ⭐ 497 | 🐛 90 | 🌐 TypeScript | 📅 2023-01-04 - A Webpack plugin to automatically reload browser extensions during development.
* [@wext/shipit](https://github.com/LinusU/wext-shipit) ⭐ 134 | 🐛 9 | 🌐 JavaScript | 📅 2021-06-12 - Tool to automatically publish to Chrome Web Store, Mozilla Addons and Opera Addons.
* [chrome-ext-downloader](https://github.com/jiripospisil/chrome-ext-downloader) ⚠️ Archived - Download any extension on Chrome Web Store to see how they do it.
* [webpack-target-webextension](https://github.com/awesome-webextension/webpack-target-webextension) ⭐ 49 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-14 - Adds code-splitting support to WebExtensions build with Webpack.
* [chromepet](https://github.com/ZenHubIO/chromepet) ⭐ 33 | 🐛 5 | 🌐 JavaScript | 📅 2014-11-09 - Get notified when your new version has been published.
* [chrome-store-api](https://github.com/acvetkov/chrome-store-api) ⭐ 31 | 🐛 2 | 🌐 JavaScript | 📅 2021-02-12 - Chrome Web Store API wrapper.
* [wext-manifest-loader](https://github.com/abhijithvijayan/wext-manifest-loader) ⭐ 28 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-04 - Webpack loader that lets you specify `manifest.json` properties to appear only in specific browsers.
* [webextension-manifest-loader](https://github.com/jsmnbom/webextension-manifest-loader) ⚠️ Archived - Webpack loader that loads browser tailored manifest.json. It also imports all importable properties, allowing you to have 'manifest.json' as your only webpack entry point.

## Testing

* [sinon-chrome](https://github.com/acvetkov/sinon-chrome) ⭐ 442 | 🐛 37 | 🌐 JavaScript | 📅 2021-07-12 - Mocks the Chrome Extensions API for testing.
* [addons-linter](https://github.com/mozilla/addons-linter) ⭐ 363 | 🐛 71 | 🌐 JavaScript | 📅 2026-08-21 - Validate an extension against Mozilla's guidelines.
* [webextensions-jsdom](https://github.com/stoically/webextensions-jsdom) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2022-06-30 - Load popup, sidebar and background with JSDOM based on the manifest.json.
* [webextensions-api-fake](https://github.com/stoically/webextensions-api-fake) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2020-06-08 - In-memory WebExtensions API Fake Implementation (includes TypeScript types).
* [webextensions-api-mock](https://github.com/stoically/webextensions-api-mock) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2020-01-29 - WebExtensions API as sinon stubs (includes TypeScript types).
* [webextensions-schema](https://github.com/stoically/webextensions-schema) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2022-06-24 - Programmatically consume the WebExtensions Schema JSON files.

## Boilerplates

* [WXT](https://github.com/wxt-dev/wxt) ⭐ 10,391 | 🐛 191 | 🌐 TypeScript | 📅 2026-08-22 - Next-gen framework for developing web extensions
* [browser-extension-template](https://github.com/fregante/browser-extension-template) ⭐ 848 | 🐛 4 | 🌐 JavaScript | 📅 2025-02-03 - Barebones boilerplate with parcel, options handler and auto-publishing.
* [generator-web-extension](https://github.com/webextension-toolbox/generator-web-extension) ⭐ 317 | 🐛 13 | 🌐 JavaScript | 📅 2023-03-01 - WebExtension generator that creates everything you need to get started with cross-browser web-extension development.
* [create-webextension](https://github.com/rpl/create-webextension) ⭐ 25 | 🐛 11 | 🌐 JavaScript | 📅 2018-11-15 - Yarn WebExtension generator.

## Sample Extensions

These are simple and modern WebExtensions repositories that could help you figure out where pieces go, including automatic deployment via GitHub Actions.

* [mdn/webextension-examples](https://github.com/mdn/webextensions-examples) ⭐ 4,471 | 🐛 32 | 🌐 JavaScript | 📅 2026-07-30 - Various example extensions curated for the MDN documentation.
* [npmhub](https://github.com/npmhub/npmhub) ⭐ 833 | 🐛 5 | 🌐 Svelte | 📅 2024-08-13
* [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github) ⚠️ Archived

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
