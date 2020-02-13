**Niote:** Work In progress.

This is a thme with lots of powers, but an extremely simple build, thanks to [Hugo Modules](https://gohugo.io/hugo-modules/). Only one (optional) NPM dependency (PostCSS).

Some bullet points:

* Styling via [Bulma](https://bulma.io/) with custom `SCSS` palette/variable file.
* Font Awesome 5 icons.
* DOM manipulation and other JS goodness via [AlpineJS]( https://github.com/alpinejs/alpine).
* [Turbolinks](https://github.com/turbolinks/turbolinks) for navigation.
* PostCSS (TODO)
* Navigation: Top level [Hugo menu](https://gohugo.io/content-management/menus/), left side section-tree, section breadcrumbs.
* Cover and featured image handling with image processing.

## Tips

* Add class `data-turbolinks-permanent` to any DOM node with JavaScript state you want to preserve. This node must have an `id`.

## Credits

The layout of this theme is based on the [Bulma Hero Template](https://github.com/BulmaTemplates/bulma-templates/blob/master/templates/hero.html), MIT licensed, copyright (c) 2016 Daniel Supernault, see [License](https://github.com/bulmatemplates/bulma-templates/blob/master/LICENSE).