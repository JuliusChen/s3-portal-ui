[![Build Status](https://travis-ci.org/JuliusChen/s3-portal-ui.svg?branch=dev)](https://travis-ci.org/JuliusChen/s3-portal-ui)
[![Dependency Status](https://www.versioneye.com/user/projects/5880970a452b830054c172ce/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/5880970a452b830054c172ce)

# S3 Portal

> Constructing...

### Requirement

`Node >= 6.1.0`

### Usage

Copy the `./config.example.js` file to `./config.js` and configure the file for your environment:

```sh
$ cp config.example.js config.js
$ vim config.js
```

Install dependencies:

```sh
$ npm install
```

Open another terminal and running below command:

```sh
$ npm start
```

`http://localhost:3001` will automatically open with browser-sync.

### Build

Build the bundle js:

```sh
$ npm run build
```

The static file will build on `./dist`.

You can start the production server:

```sh
$ npm run prod
```

### Test

```sh
$ npm test
```

### Lint

```sh
$ npm run lint
```
