# node-pre-commit
Pre-commit Git hook for NodeJS

This is adapted version of the pre-commit package.

Link to original code: [Original code](https://github.com/observing/pre-commit)

Adapted version works under Windows too.

Package was tested under SourceTree.

Example of package.json:

``` javascript
...
  "scripts": {
    "test": "mocha test"
  },
  "pre-commit": [
    "test"
  ],
...
  "devDependencies": {
    "chai": "",
    "node-pre-commit": "" 
  }

```