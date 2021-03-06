## [2.0.1](https://github.com/fpipita/babel-plugin-css-tag-postcss/compare/v2.0.0...v2.0.1) (2021-03-05)

### Bug Fixes

- don't fail when the number of expressions is greater than 10 ([37995bd](https://github.com/fpipita/babel-plugin-css-tag-postcss/commit/37995bdfb671cbb54a7279af81a6a1094fa15681)), closes [#6](https://github.com/fpipita/babel-plugin-css-tag-postcss/issues/6)

# [2.0.0](https://github.com/fpipita/babel-plugin-css-tag-postcss/compare/v1.0.3...v2.0.0) (2020-09-20)

### Features

- add support for PostCSS 8 ([ac2e70f](https://github.com/fpipita/babel-plugin-css-tag-postcss/commit/ac2e70fb2a25fb9c2e6a4cfac6dd08858c149024))
- switch to conditional exports ([466ac22](https://github.com/fpipita/babel-plugin-css-tag-postcss/commit/466ac227244fc90c7e0b2d546e32e4bc6fe6b45a))

### BREAKING CHANGES

- Removed the old cjs specifier "@fpipita/babel-plugin-css-tag-postcss/commonjs",
  both cjs and esm versions are available through "@fpipita/babel-plugin-css-tag-postcss".

## [1.0.2](https://github.com/fpipita/babel-plugin-css-tag-postcss/compare/v1.0.1...v1.0.2) (2020-07-27)

## 1.0.1 (2020-07-27)

### Bug Fixes

- handle expression showing in PostCSS-expanded rule ([77a9b26](https://github.com/fpipita/babel-plugin-css-tag-postcss/commit/77a9b265b4597eff7ce49180c6182265ba16068d))

### Features

- initial implementation ([a252f56](https://github.com/fpipita/babel-plugin-css-tag-postcss/commit/a252f565286f7fee34bc5053dc2aa7917d514ddd)), closes [#1](https://github.com/fpipita/babel-plugin-css-tag-postcss/issues/1) [#2](https://github.com/fpipita/babel-plugin-css-tag-postcss/issues/2) [#3](https://github.com/fpipita/babel-plugin-css-tag-postcss/issues/3)
