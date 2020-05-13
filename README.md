# EOS Costa Rica standard theme
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
At EOS Costa Rica we believe is important to have a standard theme across our several projects, that will allow us a faster developments of our web apps and at the same time it's availabe for anyone who will want to use it.
# Instalation
```
$ npm i -S @eoscostarica/eoscr-theme
```
If you prefer to use yarn:
```
yarn add @eoscostarica/eoscr-theme
```
> Note: _if  you're reading this from Github Packages, **yarn is not supported yet**. You can see the entire list of supported package managers right [here](https://help.github.com/en/packages/publishing-and-managing-packages/about-github-packages#supported-clients-and-formats)_.
# Usage
```
import { EOSCR_THEME } from "@eoscostarica/eoscr-theme";
...
...
let primaryColor = EOSCR_THEME.colors.primary.base;
```
# Project structure
```
├── dist
├── src
|  ├── index.ts
├── test 
├── package.json
├── README.md
└── tsconfig.json
```
# Theme object general structure
```
EOSCR_THEME
├── colorScheme
|   ├── primary
|   |   ├── ...
|   |   secondary
|   |   ├── ...
├── typography
|   ├── fontFamilies
|   |   ├── ...
|   ├── h1
|   |   ├── ...
|   ├── h2
|   |   ├── ...
|   ├── ...
|   |   ├── ...
```
You can see the entire raw file [here](https://raw.githubusercontent.com/eoscostarica/eoscr-theme/master/src/index.ts).
## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/JustinCast"><img src="https://avatars1.githubusercontent.com/u/17890146?v=4" width="100px;" alt=""/><br /><sub><b>JustinCast</b></sub></a><br /><a href="https://github.com/eoscostarica/eoscr-theme/commits?author=JustinCast" title="Code">💻</a> <a href="https://github.com/eoscostarica/eoscr-theme/commits?author=JustinCast" title="Documentation">📖</a> <a href="#projectManagement-JustinCast" title="Project Management">📆</a> <a href="#maintenance-JustinCast" title="Maintenance">🚧</a></td>
    <td align="center"><a href="http://eoscostarica.io"><img src="https://avatars1.githubusercontent.com/u/1179619?v=4" width="100px;" alt=""/><br /><sub><b>Jorge Murillo</b></sub></a><br /><a href="#design-murillojorge" title="Design">🎨</a></td>
    <td align="center"><a href="https://eoscostarica.io"><img src="https://avatars0.githubusercontent.com/u/5632966?v=4" width="100px;" alt=""/><br /><sub><b>Xavier Fernandez</b></sub></a><br /><a href="https://github.com/eoscostarica/eoscr-theme/pulls?q=is%3Apr+reviewed-by%3Axavier506" title="Reviewed Pull Requests">👀</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!