# ng-packagr-bundle-deps

Run `npm test` to:
- build a private library
- build a wrapper library that depends on the private library
- install the wrapped library and consumes it in a node app

If it works, the last line of the output should be `libWrapper.wrappedNumber 42`.