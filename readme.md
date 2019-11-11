# Web setup

Monorepa based on [lerna](https://lerna.js.org/) and [yarn workspace](https://yarnpkg.com/lang/ru/docs/workspaces/)

## Install

```sh
npm install -g lerna
yarn bootstrap
```

## Add package

- ```cp ./package/sample ./package/newPackage```
- edit name ```./package/newPackage/package.json```
- ```yarn bootstrap```
- ```yarn dev --scope newPackage```

## Scripts
- ```yarn bootstrap``` install all dependencies and symblink
- ```yarn ls``` list packages
- ```yarn dev``` run development on all packages
- ```yarn dev --scope packageName``` run development on define package
- ```yarn clean``` clean dependencies packages (does not touch root)

## Dev dependencies
- ```node```
- ```yarn```
- ```typescript```
- ```lerna```
- ```parsel-bundler```

## Dependencies
- ```react```
- ```react-dom```
