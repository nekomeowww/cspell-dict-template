# CSpell Example Org Terms Dictionary

## TODO...

- [ ] Replace `@example-org/cspell-dict` with the actual dict you want.
- [ ] Replace `@example-org` with the actual organization scope, namespace.
- [ ] Replace `Example Org` with the actual organization name.
- [ ] Replace `github.com/example-org` with the actual organization of GitHub.
- [ ] Replace `github.com/example-org/cspell-dicts` with the actual repository name.
- [ ] Replace `example-dict` with the actual dictionary name.
- [ ] Customize the `README.md` file.
- [ ] Customize the `cspell-ext.json` file.
- [ ] Customize the `cspell-tool.config.yaml` file.
- [ ] Add more words into dict:
  - [ ] `src/example-dict.dic.txt`

## How to develop based on this template

1. Clone
2. Replace `@example-org/cspell-dict` with the actual dict you want.
3. Replace `@example-org` with the actual organization scope, namespace.
4. Replace `Example Org` with the actual organization name.
5. Replace `github.com/example-org` with the actual organization of GitHub.
6. Replace `github.com/example-org/cspell-dicts` with the actual repository name.
7. `pnpm install`
8.  Build the package, `pnpm run build`.
9.  Tag and push, `pnpm exec bumpp`.
10. Publish, `pnpm publish`.

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

### Written with ♥
