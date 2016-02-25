# typings-fs-promise
A Typescript type definition for [fs-promise](https://github.com/kevinbeaty/fs-promise).

## Install

Use the [typings](https://github.com/typings/typings) utility to install the type definition. TSD is not supported, as it is deprecated.

## About fs-extra

As fs-promise automatically wraps [fs-extra](https://github.com/jprichardson/node-fs-extra) if it is installed, all fs-extra functions are listed in the type definition.

As type definitions are staticaly typed, invoking a promisified fs-extra function will always compile, but might fail at runtime if fs-extra has not been installed
