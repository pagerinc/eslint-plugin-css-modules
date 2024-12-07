This fork fixes a problem in the original (no longer maintained) repo, where a .scss file would cause eslint errors if it included modern
syntax such as `@use`. It also adds some niceties, such as:
- Throws an error if the imported file cannot be found (silent failure in the original repo)
- Throws an error out if the imported file cannot be parsed (silent failure in the original repo)

Please check the documentation for the original repo [here](https://github.com/atfzl/eslint-plugin-css-modules). 
