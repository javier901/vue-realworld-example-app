
# ![RealWorld Example App](./static/rwv-logo.png)

This codebase was created to demonstrate a fully fledged fullstack application built with **Vue.js** including CRUD operations, authentication, routing, pagination, and more.

We've gone to great lengths to adhere to the **Vue.js** community styleguides & best practices.


## Getting started

Before contributing please read the following:
```bash
# install editorconfig globally
> npm install -g editorconfig
```

The stack is built using [vue-cli webpack](https://github.com/vuejs-templates/webpack) so to get started all you have to do is:

``` bash
# install dependencies
> yarn install
# serve with hot reload at localhost:8080
> yarn serve
```

Other commands available are:

``` bash
# build for production with minification
yarn run build

# run unit tests
yarn test
```

## To know

Current arbitrary choices are:

- Vuex modules for store
- Vue-axios for ajax requests
- 'rwv' as prefix for components

These can be changed when the contributors reach a consensus.

## FAQ
  Vue.js 3 will likely introduce breaking changes on how Vue.js applications will look like. For example, the Vue.js Function API might be introduced. This would cause a lot of our components to change in the overall structure. The changes would be minimal though. With the `vue-function-api` plugin, these changes could be applied already. The problem is that multiple integrations are not working with the plugin. There are intentions to make this work, but for the time being, we should rather focus on different areas. If you still want to be experimental with it, we are happy to get a Pull Request with some experimental feature implementations.
</details></p>
