# Webpack Dependency Tools

Scan your webpack project for cyclic-dependencies.

### Usage

```
let CyclicDependencyChecker = require("webpack-dependency-tools").CyclicDependencyChecker;
webpackConfig.plugins.push(
	new CyclicDependencyChecker()
);

webpackConfig.profile = true;
webpackConfig.stats = "verbose";
```