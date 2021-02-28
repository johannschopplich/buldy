<p align="center">
  <img src="./assets/logo.svg" alt="Logo of Buldy framework" height="114">
</p>

<h3 align="center">Buldy</h3>

<p align="center">
  Modern CSS framework distilled from the best of larger frameworks<br>
</p>

<br>

## Buldy

### Key Features

> Built using the tastiest flavours of larger frameworks this minimal CSS framework is a suitable companion and starter point for small web projects as well as big design systems.

- 🏸&nbsp; Everything you need to create a solid project
- 📖&nbsp; Typography system where all font sizes are intertwined
- 📐️&nbsp; Powerful responsive spacing system using multipliers of a unit value
- 🏗&nbsp; Easily editable and extendable CSS custom properties
- 🍱&nbsp; A handful of elements, components & utilities
- 🎯&nbsp; No preprocessor necessary — [just plug'n'play](https://github.com/johannschopplich/buldy/blob/master/dist/buldy.css)
- ✅&nbsp; Good Semantics

### Introduction

Buldy is a CSS framework. As such, the sole output is a single CSS file: [buldy.css](https://github.com/johannschopplich/buldy/blob/master/dist/buldy.css)

You can use that file out of the box and adapt it to your needs by changing the corresponding colors, typography, spacing and much more CSS custom properties.

## Folder Structure — What's Included?

Some notes about the folder structure with some additional comments on important files.

<details>
<summary><b>Expand folder tree</b></summary>

```sh
buldy/scss/
|
|   # Core functions and mixin configuration
├── abstracts/
|   |
|   |   # Breakpoint viewport sizes and functions for responsiveness
|   ├── _breakpoints.scss
|   |
|   |   # Functions like fluid type to elegantly scale type and space w/o breakpoints
|   ├── _functions.scss
|   |
|   |   # Sass mixins for various components
|   └── _mixins.scss
|
|   # Main stem of the framework
├── base/
|   |
|   |   # Tiny CSS reset that covers the basics, may also be used standalone
|   |   # Built on top of Bootstrap's # [`reboot.scss`](https://github.com/twbs/bootstrap/blob/main/scss/_reboot.scss), Jeremy Thomas' (creator of Bulma) [`minireset.sass`](https://github.com/jgthms/minireset.css/blob/master/minireset.css)
|   |   # and Jonathan Neal's [`sanitize.css`](https://github.com/csstools/sanitize.css/blob/master/sanitize.css)
|   ├── resets.scss
|   |
|   |   # Custom properties Fluid type and space scales, semantic color definitions, themes and more
|   ├── variables.scss
|   |
|   |   # Scoped theme containers via `[data-theme]` 
|   ├── themes.scss
|   |
|   |   # Extends standalone resets with further generic opiniated styles
|   ├── generic.scss
|   |
|   |   # Support for `:focus-visible`
|   └── accessibility.scss
|
|   # Design the structure of your webpage with these CSS classes
├── layout/
|   |
|   |   # Simple way to build responsive columns with Flexbox
|   ├── columns.scss
|   |
|   |   # Simple container to center content horizontally
|   ├── container.scss
|   |
|   |   # Sass port of the [Raster Grid System](https://rsms.me/raster/) by Rasmus Andersson
|   ├── raster.scss
|   |
|   |   # Simple container to divide your page into sections 
|   ├── section.scss
|   |
|   |   # Let elements flow vertically or horizontally
|   └── stack.scss
|
|   # Essential interface elements that only require a single CSS class
├── components/
|   |
|   |   # Container for fixed or auto-growing responsive embeds
|   ├── aspect-ratio.scss
|   |
|   |   # A colored box to contain other elements
|   ├── box.scss
|   |
|   |   # Buttons in different colors, sizes, and states
|   ├── button.scss
|   |
|   |   # Handle WYSIWYG generated content, where only HTML tags are available
|   ├── content.scss
|   |
|   |   # Basic indispensable form controls
|   ├── form.scss
|   |
|   |   # Classic modal overlay
|   ├── modal.scss
|   |
|   |   # Simple headings to add depth to your page
|   └── title.scss
|
|   # Modular helper classes to handle common layout tasks
├── helpers/
|   |
|   |   # Adds bottom gap to other `.block` elements
|   ├── block.scss
|   |
|   |   # Essentials
|   ├── miscellaneous.scss
|   |
|   |   # Hide content visually but make it available for screen readers
|   ├── screen-reader.scss
|   |
|   |   # Make any element clickable by stretching”a nested link
|   └── stretched-link.scss
|
|   # For faster mobile-friendly and responsive development
|   # Includes utility classes for showing, hiding, aligning, sizing and spacing content
├── utilities/
|   |
|   |   # Runner to create all utility classes from `utilities.scss`
|   ├── _api.scss
|   |
|   |   # The utility generator function
|   ├── _generator.scss
|   |
|   |   # Editable list to generate utilities programmatically
|   └── utilities.scss
|
|   # Main entry point
└── buldy.scss
```

</details>

## How Did We Get Here

Well, yet another framework which seeks to be used? Yes. I used Bulma and Bootstrap heavily over the years – Bulma's class naming syntax was a breeze to work with, although I preferred Bootstraps grid breakpoints. I often found myself removing unwanted stuff from every big framework I worked with (Bulma came as close as it can probably get to be the perfect allrounder).

One influental dev once said that every programmer should develop his own framework. I guess he's right as this is my try. I wanted to use a framework which only includes the essentials a project needs. Everything else should be added per project. Thoroughly searching the interweb didn't brought me closer to what I wished to find.

Then Codyhouse came along and presented the world with a series of articles and shortly after published their own [framework](https://github.com/CodyHouse/codyhouse-framework). The use of CSS custom properties for a framework blew my mind. Which is pretty common nowadays, even Bootstrap 5 adapts them. But again, some design choices incorporated into the framework weren't my taste. So I used their great ideas and created my own framework.

Improvements and suggestions are always welcome.

## Browsers Support

All of the latest and greatest browsers. Including Safari.

## Credits

Big shoutout to [@CodyHouse](https://github.com/CodyHouse) and [@jgthms](https://github.com/jgthms) for their inspiring frameworks.

## License

Code released under the [MIT License](https://github.com/johannschopplich/buldy/blob/master/LICENSE).
