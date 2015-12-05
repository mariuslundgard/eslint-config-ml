# eslint-config-ml

A complete [ESLint](http://eslint.org/) configuration.

## Installation

First install the package using [npm](http://npmjs.com/):

```sh
npm install eslint-config-ml
```

Then create an `.eslintrc` file:

```json
{
  "extends": [
    "eslint-config-ml"
  ]
}
```

## Overriding rules

If you prefer to use semicolons, then add the `semi` rule like this:

```json
{
  "extends": [
    "eslint-config-ml"
  ],
  "rules": {
    "semi": [2, "always"]
  }
}
```

Similarly, other rules can be overridden. Check the list of available [ESLint rules](http://eslint.org/docs/rules/).
