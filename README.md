JS to JSX
=========

Babel plugin to convert from desugared React.DOM CallExpressions -> the equivalent JSX. Currently used to migrate to ES6 from other compile to JS languages.

`cat example.ls | lsc -cb --no-header | node transform.js | esformatter -c format.json`