<p align="center">
<a href="https://bootstrap-vue.github.io">
    <img src="https://github.com/bootstrap-vue/bootstrap-vue/raw/master/banner.png" width="300px">
</a>
<br>
<a href="https://circleci.com/gh/bootstrap-vue/bootstrap-vue">
    <img alt="" src="https://img.shields.io/circleci/project/github/bootstrap-vue/bootstrap-vue/master.svg?style=flat-square">
</a>
<a href="https://www.npmjs.com/package/bootstrap-vue">
    <img alt="" src="https://img.shields.io/npm/dt/bootstrap-vue.svg?style=flat-square">
</a>
<a href="https://www.npmjs.com/package/bootstrap-vue">
    <img alt="" src="https://img.shields.io/npm/v/bootstrap-vue.svg?style=flat-square">
</a>
<a href="https://github.com/sindresorhus/xo">
    <img alt="" src="https://img.shields.io/badge/code_style-XO-5ed9c7.svg?style=flat-square">
</a>
<a href="https://v4-alpha.getbootstrap.com">
    <img alt="" src="https://img.shields.io/badge/bootstrap-4.0.0--alpha.6-800080.svg?style=flat-square">
</a>
<a href="https://vuejs.org">
    <img alt="" src="https://img.shields.io/badge/vue.js-2.2.x-green.svg?style=flat-square">
</a>
<a href="https://bootstrap-vue.now.sh/">
    <img alt="" src="https://bootstrap-vue.now.sh/badge.svg">
</a>

</p>

> [Bootstrap 4](https://v4-alpha.getbootstrap.com/) components for [Vue.js 2](https://vuejs.org/)

 ⚠ [Release Notes](https://github.com/bootstrap-vue/bootstrap-vue/releases)

# ✔ Getting started
Please refer to [Official Documentation](https://bootstrap-vue.github.io) for setup guide, examples and documentation.

1. Download dependencies:
```bash
yarn add bootstrap-vue
yarn add bootstrap@4.0.0-alpha.6
yarn add -D style-loader
```

2. Register BootstrapVue in your app entrypoint:
```js
import Vue from 'vue'
import BootstrapVue from 'bootstrap-vue';

Vue.use(BootstrapVue);
```

3. Import styles using style-loader:
```js
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
```

##### For users of Webpack or Webpack-Simple from `vue-cli` follow these instructions:
1. Download the dependencies:
```bash
yarn add bootstrap-vue
yarn add bootstrap@4.0.0-alpha.6
yarn add -D style-loader
```

2. In `src/main.js`, add the following lines, in priority order:
```js
import Vue from 'vue';
/* ( there may be other imports here ) */
import BootstrapVue from 'bootstrap-vue/dist/bootstrap-vue.esm';
import 'bootstrap-vue/dist/bootstrap-vue.css';
import 'bootstrap/dist/css/bootstrap.css';
/* ( there may be other imports here ) */

Vue.use(BootstrapVue);
```

#### Note on style-loader:
If you are unable or do not want to add style-loader as a developer dependency, you have to
manually include both [Bootstrap's](https://v4-alpha.getbootstrap.com/getting-started/download/)
and [BootstrapVue's](https://unpkg.com/bootstrap-vue@latest/dist/bootstrap-vue.css) CSS files
in your bundle or reference them from `static/` via `index.html`.

# License
MIT
