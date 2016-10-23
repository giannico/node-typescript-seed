# node-typescript-seed

A Node/TypeScript seed project.

This is a very basic project that allows you to get up and running easily with Node and TypeScript.

-----

### Features

* TypeScript 2 support with modules
* Watch Mode
* Minimal dependencies (no external build system or npm globals required)
* Works on OSX and Windows

-----

### Quick Start

```sh
# clone the report
git clone https://github.com/giannico/node-typescript-seed node-typescript-seed

# change directory to the app
cd node-typescript-seed

# install the dependencies
npm install

# start development mode
npm run dev
```

#### Dev Configuration

When running in dev mode, the application will automatically execute each time you make a change to `app.ts` or any file that `app.ts` depends on (recursively).

Modify the auto-execution delay setting in `package.json` (defaults to 1500ms) to meet your needs. Ideally, you'll choose a number that will cause your application to only restart once, each time you make typical development changes. The optimal delay time will vary depending on the size of your project and your development machine.

-----

### Other NPM tasks

After running `npm install` once, you can:

#### Build the app

```sh
npm run build
```

#### Run the app once

```sh
npm start
```

#### Run the linter

Tailor the `tslint.json` to your likings

```sh
npm run lint
```