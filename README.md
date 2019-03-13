<p align="center">
  <img src="docs/logo.svg" alt="Buldy logo" width="173" height="86">
</p>

<p align="center">
  A beautiful minimal CSS framework utilizing custom properties.<br>
  <a href="https://github.com/jschopplich/buldy/issues"><img src="https://img.shields.io/github/issues/jschopplich/buldy.svg"></a>
</p>

<br>

# Buldy

The framework serves the following purposes:

- ⚡️&nbsp; Everything you need to create a solid project
- 🗨&nbsp; Typography system where all font sizes are intertwined 
- 📐️&nbsp; Powerful **responsive spacing system** using multipliers of the unit value
- 🌈&nbsp; Easy editable and extendable CSS variables
- 🎈&nbsp; No preprocessor necessary if unwanted — [just plug'n'play](https://github.com/jschopplich/buldy/blob/master/dist/buldy.css)
- 📖&nbsp; Magical 12 column grid plus [iota grid](https://github.com/korywakefield/iota) included
- 🏗&nbsp; Comes with a handful of components &amp; utilities
- ✅&nbsp; Good Semantics

Buldy is a CSS framework. As such, the sole output is a single CSS file: [buldy.css](https://github.com/jschopplich/buldy/blob/master/dist/buldy.css)
You can use that file out of the box and adapt it to your needs by changing the corresponding colors, typography, spacing etc. CSS variables.

If [Bulma](https://github.com/jgthms/bulma) and [CodyHouse's framework](https://github.com/CodyHouse/codyhouse-framework) would have children: This is the one. Built using the best of both worlds this minimal css framework is a suitable companion and starter point for small web projects as well as big design systems.

## What's included

- A Tiny modern CSS reset that covers the basics, built on top of Bootstrap's [`reboot.scss`](https://github.com/twbs/bootstrap/blob/master/scss/_reboot.scss), Jeremy Thomas' (creator of Bulma) [`minireset.sass`](https://github.com/jgthms/minireset.css/blob/master/minireset.css), Jonathan Neal's [`sanitize.css`](https://github.com/csstools/sanitize.css/blob/master/sanitize.css) and Sindre Sorhus' [`modern-normalize.css`](https://github.com/sindresorhus/modern-normalize/blob/master/modern-normalize.css)
Powerful responsive spacing system are multipliers of the unit value
- Color (primary, accent, light and dark variations), spacing and component variables
- Four different Basic button styles (normal, primary, accent and text)
- A simple container to center your content horizontally
- Hero, section, form and image elements
- Single class to handle WYSIWYG generated content, where HTML should be available 
- Responsive columns layout powered by Flexbox (heavily inspired by Bulma)
- Essential helpers

## How did we get here

Well, yet another framework which seeks to be used? Yes. I used Bulma and Bootstrap heavily over the years — Bulma's class naming syntax was a breeze to work with, although I preferred Bootstraps grid breakpoints. I often found myself removing unwanted stuff from every big framework I worked with (Bulma came as close as it can probably get to be the perfect allrounder).

One influental dev once said that every programmer should develop his own framework. I guess he's right as this is my try. I wanted to use a framework which only includes the essentials a project needs. Everything else should be added per project. Thoroughly searching the interweb didn't brought me closer to what I wished to find.

Then Codyhouse came along and presented the world with a series of articles and shortly after published their own framework:
- Part 1: [Typography](https://medium.com/codyhouse/create-your-design-system-part-1-typography-7c630d9092bd)
- Part 2: [Grid & Layout](https://medium.com/codyhouse/create-your-design-system-part-2-grid-layout-aa961d59b8d6)
- Part 3: [Colors](https://medium.com/codyhouse/create-your-design-system-part-3-colors-798e4729921f)
- Part 4: [Spacing](https://medium.com/codyhouse/create-your-design-system-part-4-spacing-895c9213e2b9)
- Part 5: [Icons](https://medium.com/codyhouse/create-your-design-system-part-5-icons-594f39cfb1b)
- Part 6: [Buttons](https://medium.com/codyhouse/create-your-design-system-part-6-buttons-58e2eda2173e)

The use of CSS custom properties for a framework blew my mind. But again, some design choices incorporated into the framework weren't my taste. So I used their great ideas and created my own framework.

Improvements and suggestions are always welcome.

## License

Code released under the [MIT License](https://github.com/jschopplich/buldy/blob/master/LICENSE).
