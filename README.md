# patternfly-webcomponents

PatternFly design Web Components using SASS from [@patternfly/patternfly](https://github.com/patternfly/patternfly-next).

This repo is currently being used to do Proof of Concept work: **_NO COMPONENTS ARE PRODUCTION READY_**

## Getting started
1. Clone submodules
```sh
git submodule update --init
```
2. Install dependencies using yarn workspaces:
```sh
yarn install
```
3. Start our custom watch + es-dev-server script. Open http://localhost:9000/demos/index.html
```sh
yarn start
```
OR

4. Start our React Storybook
```sh
yarn storybook
```

## Creating a new component
I've written some custom scaffolding tools.
```sh
yarn generate componentName
```
