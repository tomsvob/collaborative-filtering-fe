# \<bi-vwm-fe\>

Frontend application for Collaborative filtering project
Backend - https://github.com/tomsvob/collaborative-filtering-be

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
$ yarn polymer serve build/es5-bundled
```

## Overview

### Admin section

Manually start recommendation algorithm to update recommended films for each user.
Admin can set parameters of algorithm.

### User section

User can search for films, display recommended and already rated films. User can update rating for each film in UI.