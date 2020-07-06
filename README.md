# Lerna PoC

### How to install?

```sh
npm ci
npm run lerna bootstrap
```

### How to add sibling packages?

* Manually add package to `package.json`
* Run `npm run lerna bootstrap`
* Run `npm install` to update `package-lock.json`

More info: https://github.com/lerna/lerna/issues/200

### How to publish?

```sh
npm run lerna publish from-package
# Add `-- -y` to skip prompts (useful for CI)
# Add `--access public` for scoped public packages
```

### How to update package version?

Simply update the version in the `package.json` and `package-lock.json`.
You can also update the version in dependent packages.
