# Blocss Dimensions – v1.1.4

A [Blocss](https://github.com/Blocss/blocss/) collection of utility classes for low-level CSS dimensions.

Read more about [Blocss](https://blocss.github.io/blocss).

## Installation

    $ bower install --save blocss-dimensions

## Available classes
Note: these are defaults, you can alter the names with variables

* `.u-x-x`: Gives an element width
* `.push-x-x`: Pushes an element to the right
* `.pull-x-x`: Pulls an element to the left

You can alter the `$blocss-divisions` variable to create several proportional divisions.
For example, `2 4 6 12` will let you use the `.u-1-2`, `.u-2-4`, `.u-3-6`, and
`.u-6-12` classes to specify that an element should take up 50% of its container.

## Available settings

* `$blocss-dimensions-namespace` - Prefixes classes with a namespace, defaults to `$blocss-namespace`
* `$blocss-dimensions-responsive-modifier` - Prefixes classes with a namespace, defaults to `$blocss-responsive-modifier`
* `$blocss-use-units` - enables/disables unit generation, defaults to `true`
* `$blocss-use-push` - enables/disables push generation, defaults to `false`
* `$blocss-use-pull` - enables/disables pull generation, defaults to `false`
* `$blocss-divisions` - create several proportional divisions as read above, defaults to `12` for twelve colums
* `$blocss-breakpoint-has-units` - Defines which namespaced breakpoints you would like to generate units, defaults to `()`
* `$blocss-breakpoint-has-push` - Defines which namespaced breakpoints you would like to generate push, defaults to `()`
* `$blocss-breakpoint-has-pull` - Defines which namespaced breakpoints you would like to generate pull, defaults to `()`
* `$blocss-name-units` - the name prefix of units, defaults to `u`
* `$blocss-name-push` - the name prefix of push, defaults to `push`
* `$blocss-name-pull` - the name prefix of pull, defaults to `pull`

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+
