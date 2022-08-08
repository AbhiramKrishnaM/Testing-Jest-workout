## Using Es6 export/import statements in jest

to use this simple create an .babelrc file

```
{
  "env": {
    "test": {
      "plugins": ["@babel/plugin-transform-modules-commonjs"]
    }
  }
}
```
