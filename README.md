# Lerna PoC

### How to install?

```
npm ci
npm run lerna bootstrap
```

### How to add sibling packages?

* Manually add package to `package.json`
* Run `npm run lerna bootstrap`
* Run `npm install` to update `package-lock.json`

More info: https://github.com/lerna/lerna/issues/200
