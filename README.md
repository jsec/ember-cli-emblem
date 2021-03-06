# Ember-cli-emblem

This is an ember-cli addon that brings support for
[Emblem.js](http://emblemjs.com) templates.

This printer is based on version 0.5.0+ of Emblem. It compiles `.embl`,
`.emblem` and `.em` templates into Handlebars-syntax templates which
will then be compiled as standard `.hbs` templates by ember-cli.

Consequently, this addon should be compatible with old versions of Ember
regardless of its template dependency, and support newer (HTMLBars)
template compilation in ember-cli.

## Installation

If you are using the `broccoli-emblem-compiler` it should be removed
before using this addon: `npm uninstall --save-dev broccoli-emblem-compiler`.

* `ember install ember-cli-emblem`

## Blueprints

ember-cli-emblem supports blueprint generation for routes, components, and templates. Use the `ember generate` command to add new Emblem templates.

If you do not wish to use blueprints, an `emblemOptions` setting is available in your `config/environment.js`:

```
ENV.emblemOptions {
	blueprints: false
}
```

## Ember-CLI support

  * Versions `0.1.x`: supported
  * Versions `0.2.x`: supported

