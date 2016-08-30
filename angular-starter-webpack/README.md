# Angular2 Starter with WebPack
[![Build Status][travis-badge]][travis-badge-url]

This is a quick starter template build for webpack. The webpack library does transcompile (build) and also bundles to output directory. The template also uses webpack dev server as development server.

## Prerequisites

Node.js and npm are essential to Angular 2 development. 
    
<a href="https://docs.npmjs.com/getting-started/installing-node" target="_blank" title="Installing Node.js and updating npm">
Get it now</a> if it's not already installed on your machine.
 
**Verify that you are running at least node `v4.x.x` and npm `3.x.x`**
by running `node -v` and `npm -v` in a terminal/console window.
Older versions produce errors.

Recommend [nvm](https://github.com/creationix/nvm) for managing multiple versions of node and npm.

## Create a new project based on the QuickStart

Clone this repo into new project folder (e.g., `my-proj`).
```bash
git clone  https://github.com/anish1024/Angular/edit/master/angular-starter-webpack  my-proj
cd my-proj
```

## Install npm packages

```bash
npm install
```

> See npm and nvm version notes above

Install the npm packages described in the `package.json` and verify that it works:

> `npm install`
The `npm install` command will install all packages from package.json and setup your env.

> `npm run build`
> `npm run build:prod`
The `npm run build:prod` is for production. This command will build and output to 'dist' folder.

> `npm run server`
This command will fire the webpack dev server and also watch the file for changes for auto-compilation.

Shut it down manually with Ctrl-C.

You're ready to write your application.
