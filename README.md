# Webpack Dependency Tools

Scan your webpack project for cyclic-dependencies.

### Install

```
npm install --save webpack-dependency-tools
```

### Usage

```
let CyclicDependencyChecker = require("webpack-dependency-tools").CyclicDependencyChecker;
webpackConfig.plugins.push(
	new CyclicDependencyChecker()
);

webpackConfig.profile = true;
webpackConfig.stats = "verbose";
```