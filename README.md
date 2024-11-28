# CSpell Example Org Terms Dictionary

Example Org terms dictionary for cspell.

This is a pre-built dictionary for use with cspell.

## Installation

Global Install and add to cspell global settings.

```sh
npm install -g @example-org/cspell-dict
cspell link add @example-org/cspell-dict
```

## Uninstall from cspell

```sh
cspell link remove @example-org/cspell-dict
```

## Manual Installation

The `cspell-ext.json` file in this package should be added to the import section in your cspell.json file.

```javascript
{
    // …
    "import": ["@example-org/cspell-dict/cspell-ext.json"],
    // …
}
```

## Building

Building is only necessary if you want to modify the contents of the dictionary. Note: Building will take a few minutes for large files.

```sh
npm run build
```

## License

MIT

> Some packages may have other licenses included.
