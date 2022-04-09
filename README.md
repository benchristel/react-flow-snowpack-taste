# React, Flow, Snowpack, @benchristel/taste

This template repo lets you quickly get a
[jamstack](https://jamstack.org/) frontend up and running
using a set of technologies chosen for simplicity and fast
feedback.

It assumes you have `yarn` and `node` installed.

## Setup

1. Click the [**"Use this template"**](https://github.com/benchristel/react-flow-snowpack-taste/generate) button on GitHub to create a new project based on this template repo.
1. Clone the repo.
1. Change the package name, author, and license in `package.json`, and the `<title>` in `index.html`.

## Dev Commands

| command | effect |
| ------- | ------- |
| **yarn&nbsp;dev** | serves the app on port 8080 and opens it in your default browser |
| **yarn&nbsp;build** | builds the app into the `docs` dir (the strange choice of directory name ensures you can deploy on GitHub Pages) |
| **yarn&nbsp;flow** | typechecks your code |

## Running Tests

Tests run automatically in the browser on each page load,
and the page reloads whenever you change a source file.

See [@benchristel/taste](https://npmjs.com/package/@benchristel/taste) for more info about the test framework.

## Known Issues

The dev server crashes sometimes (when you rename a JS file? TODO: figure out exactly what the trigger is).
