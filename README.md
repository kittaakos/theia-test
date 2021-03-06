# theia-test

Theia test repository

## Getting started

Install [nvm](https://github.com/creationix/nvm#install-script).

    curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.5/install.sh | bash

Install npm and node.

    nvm install 10
    nvm use 10

Install yarn.

    npm install -g yarn

## Running the browser example

    yarn
    yarn rebuild:browser
    cd browser-app
    yarn start

Open http://localhost:3000 in the browser.

## Running the Electron example

    yarn
    yarn rebuild:electron
    cd electron-app
    yarn start

## Developing with the browser example

Start watching of theia-test.

    cd theia-test
    yarn watch

Start watching of the browser example.

    yarn rebuild:browser
    cd browser-app
    yarn watch

Launch `Start Browser Backend` configuration from VS code.

Open http://localhost:3000 in the browser.

## Developing with the Electron example

Start watching of theia-test.

    cd theia-test
    yarn watch

Start watching of the electron example.

    yarn rebuild:electron
    cd electron-app
    yarn watch

Launch `Start Electron Backend` configuration from VS code.
