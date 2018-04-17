# \<bi-vwm-fe\>

Frontend application for Collaborative filtering project

## Install dependencies

prerequisites: yarn (npm package manager client)

```
$ yarn install
```

## Viewing Your Application

```
$ yarn serve
```

## Building Your Application

```
$ yarn build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ yarn polymer serve build/default
```

## Running Tests

```
$ yarn polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
