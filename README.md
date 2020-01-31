<p align="center">
  <img src="docs/logo.svg" alt="Buldy logo" height="114">
</p>

<p align="center">
  A beautiful minimal CSS framework utilizing custom properties.<br>
  <br>
  <a href="https://github.com/jschopplich/buldy/issues"><img src="https://img.shields.io/github/issues/jschopplich/buldy.svg"></a>
</p>

<br>

# Buldy

The framework serves the following purposes:

- ⚡️&nbsp; Everything you need to create a solid project
- 🗨&nbsp; **Typography system** where all font sizes are intertwined
- 📐️&nbsp; Powerful **responsive spacing system** using multipliers of a unit value
- 🌈&nbsp; Easily editable and extendable CSS variables
- 📖&nbsp; Magical 12 column grid
- 🏗&nbsp; A handful of elements, components &amp; utilities
- 🎈&nbsp; No preprocessor necessary — [just plug'n'play](https://github.com/jschopplich/buldy/blob/master/dist/buldy.css)
- ✅&nbsp; Good Semantics

Buldy is a CSS framework. As such, the sole output is a single CSS file: [buldy.css](https://github.com/jschopplich/buldy/blob/master/dist/buldy.css)
You can use that file out of the box and adapt it to your needs by changing the corresponding colors, typography, spacing etc. CSS variables.

If [Bulma](https://github.com/jgthms/bulma) and [CodyHouse's framework](https://github.com/CodyHouse/codyhouse-framework) would have children: This might be one of them. Built using the tastiest flavours of both worlds this minimal css framework is a suitable companion and starter point for small web projects as well as big design systems.

## What's included

- Tiny modern CSS reset that covers the basics, built on top of Bootstrap's [`reboot.scss`](https://github.com/twbs/bootstrap/blob/master/scss/_reboot.scss), Jeremy Thomas' (creator of Bulma) [`minireset.sass`](https://github.com/jgthms/minireset.css/blob/master/minireset.css), Jonathan Neal's [`sanitize.css`](https://github.com/csstools/sanitize.css/blob/master/sanitize.css) and Sindre Sorhus' [`modern-normalize.css`](https://github.com/sindresorhus/modern-normalize/blob/master/modern-normalize.css)
- Color (primary, accent and color contrast variations), typography, spacing and component variables
- Breakpoints (mobile, tablet, desktop and widescreen)
- Basic elements, including buttons, icons, titles
- Components like `.section`, `.modal`, `.control` and `.box`
- A simple `.container` to center your content horizontally
- A single `.content` class to handle WYSIWYG generated content where HTML should be available 
- Responsive `.columns` layout powered by Flexbox
- Responsive `.image` container with 16 ratio modifiers
- Essential color, typography, spacing and display helpers in order to alter every element's style 
- And much more

## How did we get here

Well, yet another framework which seeks to be used? Yes. I used Bulma and Bootstrap heavily over the years — Bulma's class naming syntax was a breeze to work with, although I preferred Bootstraps grid breakpoints. I often found myself removing unwanted stuff from every big framework I worked with (Bulma came as close as it can probably get to be the perfect allrounder).

One influental dev once said that every programmer should develop his own framework. I guess he's right as this is my try. I wanted to use a framework which only includes the essentials a project needs. Everything else should be added per project. Thoroughly searching the interweb didn't brought me closer to what I wished to find.

Then Codyhouse came along and presented the world with a series of articles and shortly after published their own [framework](https://github.com/CodyHouse/codyhouse-framework). The use of CSS custom properties for a framework blew my mind. But again, some design choices incorporated into the framework weren't my taste. So I used their great ideas and created my own framework.

Improvements and suggestions are always welcome.

## Browsers support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/samsung-internet/samsung-internet_48x48.png" alt="Samsung" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Samsung | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| last 2 versions| last 2 versions| last 2 versions| last 2 versions| last 2 versions| last 2 versions

## Credits

Big shoutout to [@CodyHouse](https://github.com/CodyHouse) and [@jgthms](https://github.com/jgthms) for their inspiring frameworks.

## License

Code released under the [MIT License](https://github.com/jschopplich/buldy/blob/master/LICENSE).
