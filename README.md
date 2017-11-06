# Blocss Dimensions – v1.2.1 - Deprecated

**This module has been moved to: ([https://github.com/Blocss/blocss](https://github.com/Blocss/blocss))**

A [Blocss](https://github.com/Blocss/blocss/) collection of utility classes for low-level CSS dimensions.

Read more about [Blocss](https://blocss.github.io/blocss).

## Installation

    $ bower install --save blocss-dimensions

## Available classes
Note: these are defaults, you can alter the names with variables

* `.unit-x-x`: Gives an element width
* `.push-x-x`: Pushes an element to the right
* `.pull-x-x`: Pulls an element to the left

You can alter the `$blocss-dimensions-divisions` variable to create several proportional divisions.
For example, `2 4 6 12` will let you use the `.unit-1-2`, `.unit-2-4`, `.unit-3-6`, and
`.unit-6-12` classes to specify that an element should take up 50% of its container.

## Available settings

* `$blocss-dimensions-namespace` - Prefixes classes with a namespace, defaults to `$blocss-namespace`
* `$blocss-dimensions-responsive-modifier` - Prefixes classes with a namespace, defaults to `$blocss-responsive-modifier`
* `$blocss-dimensions-use-units` - enables/disables unit generation, defaults to `true`
* `$blocss-dimensions-use-push` - enables/disables push generation, defaults to `false`
* `$blocss-dimensions-use-pull` - enables/disables pull generation, defaults to `false`
* `$blocss-dimensions-divisions` - create several proportional divisions as read above, defaults to `12` for twelve colums
* `$blocss-dimensions-breakpoint-has-units` - Defines which namespaced breakpoints you would like to generate units, defaults to `()`
* `$blocss-dimensions-breakpoint-has-push` - Defines which namespaced breakpoints you would like to generate push, defaults to `()`
* `$blocss-dimensions-breakpoint-has-pull` - Defines which namespaced breakpoints you would like to generate pull, defaults to `()`
* `$blocss-dimensions-name-units` - the name prefix of units, defaults to `unit`
* `$blocss-dimensions-name-push` - the name prefix of push, defaults to `push`
* `$blocss-dimensions-name-pull` - the name prefix of pull, defaults to `pull`

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+
