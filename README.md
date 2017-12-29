# ts-node-starter

Framework agnostic starter for building typescript node servers / cli's.

## Included

+ [jasmine](https://jasmine.github.io/index.html) (tests)
+ [nodemon](https://github.com/remy/nodemon) (hot-reloading)
+ [pm2](https://github.com/Unitech/pm2) (production deployment)
+ [tslint](https://github.com/palantir/tslint) (linter)

## Setup

### [NodeJS](https://nodejs.org/en)

You can install using the link above or with homebrew

```bash
brew install node
```

You should also consider using something like [nvm](https://github.com/creationix/nvm)

### [Yarn](https://yarnpkg.com)

Yarn is the package manager used in this starter. Its easy to port to [npm](http://npmjs.org/) if you'd prefer. [Click here to install](https://yarnpkg.com/en/docs/install)

Install all node dependencies

```bash
yarn
```

## Usage

Running with hot reload

```bash
yarn start
```

Run tests with hot reload

```bash
yarn run test
```

Running tests on a specific file

```bash
./node_modules/jasmine-ts/lib/index.js src/index.spec.ts
```
## Todo

+ Look into adding a coverage tool \(like [istanbul](https://istanbul.js.org/)\)
+ Look into using [commitizen](https://github.com/commitizen/cz-cli)
+ Look into [foreman](https://github.com/strongloop/node-foreman)
