## Using Es6 export/import statements in jest

to use this simply create an .babelrc file
add these lines to it

```
{
  "env": {
    "test": {
      "plugins": ["@babel/plugin-transform-modules-commonjs"]
    }
  }
}
```

now install ECMAScript 6 transform plugin

```
npm install --save-dev @babel/plugin-transform-modules-commonjs
```
