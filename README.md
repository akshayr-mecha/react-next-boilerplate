## Development

This turborepo uses [yarn](https://www.yarnpkg.com/) as a package manager and [turbo](https://turbo.build) to manage the build and dev.
To get started with `frontend-stack` development, first get things up and running, get below prerequisites setup

- Node (16.x+)
- Yarn Pkg (3.2.1+)
- Turbo (1.2.16+)

1. Install `node` using [nvm](https://github.com/nvm-sh/nvm), and set it to a version 16.x or above.
2. Install `yarn` globally using `npm install -g yarn`

**Important**: All below commands should be run in the root directory itself, as we are using a monorepo.

### Installing dependencies

To install all dependencies, run below command

```sh
yarn install
```

1. To add or update a common `dev` dependency, edit the root `package.json`, and run `yarn install` in the root directory.
2. To add a new dependency specific to a package or app, edit the respective `package.json` add the package and version and then run `yarn install` in the root directory.

### `app`

To start dev server, and go to `http://localhost:3000`

```sh
yarn dev
```

To build cloud app & start, and go to `http://localhost:3000`

```sh
yarn build
yarn start
```
