# <img src='./assets/logo.png' height='90' alt='Chipolette' />

**Chipolette** is a tiny CSS framework / Starter kit.

It's a fork from Shoelace and Bootstrap, that fully embraces CSS variables / custom properties.

No compilation required to change colors / sizes etc. Well that is if you don't want to compile. It's still written in LESS, because of nesting and other neat features that eases development of Chipolette.

It is designed to replace Bootstrap and to be used with CSS variables.

[![npm version](https://img.shields.io/npm/v/chipolette.svg?style=flat-square)](https://www.npmjs.com/package/chipolette)
[![chipolette workspace on slack](https://img.shields.io/badge/slack-chipolette-3eb891.svg?style=flat-square)](https://join.slack.com/t/radijs/shared_invite/enQtMjk3NTE2NjYxMTI2LWFmMTM5NTgwZDI5NmFlYzMzYmMxZjBhMGY0MGM2MzY5NmExY2Y0ODBjNDNmYjYxZWYxMjEyNjJhNjA5OTJjNzQ)


## Installation

To install the stable version:

```
npm install --save chipolette
```

and just import LESS version like so

```less
@import '../node_modules/chipolette/src/chipolette.less';
```

or CSS version

```css
@import '../node_modules/chipolette/dist/chipolette.css';
```

This assumes you are using [npm](https://www.npmjs.com/) as your package manager.  

If you're not, you can [access it on unpkg](https://unpkg.com/chipolette@latest/dist/chipolette.css) like so

```html
<link rel="stylesheet" href="https://unpkg.com/chipolette@latest/dist/chipolette.css" />
```

#### Browser Compatibility

Every evergreen browser and older ones that support CSS variables. But for older IE versions (and other outdated browsers) there is a polyfill.


## Stay In Touch

- [Slack](https://join.slack.com/t/radijs/shared_invite/enQtMjk3NTE2NjYxMTI2LWFmMTM5NTgwZDI5NmFlYzMzYmMxZjBhMGY0MGM2MzY5NmExY2Y0ODBjNDNmYjYxZWYxMjEyNjJhNjA5OTJjNzQ)

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, Marcis (Marcisbee) Bergmanis
