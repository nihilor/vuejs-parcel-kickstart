# vuejs-parcel-kickstart

A simple but complete kickstart scaffold for Vue.js and Parcel with Babel and Eslint.

## Why?

This kickstart provides all the necessary stuff and configuration to instantly start the prototyping of new applications. Additionally you may use this kickstart scaffold to learn coding in Vue.js. Regard: It's an opinionated stack. Other developers may prefer other file structuring and configuration.

## How?

Just clone this repository, install the dependencies and start the development server.

```
$ npm install
$ npm start
```

Afterwards, open your webbrowser and navigate to `http://localhost:1234`. Change the `./src/App.vue` and play around. Because hot loading is activated, every change will instantly be visible in the webbrowser.

## Build?

You want to build and deploy your prototype. That's easy.

```
$ npm run build
```

You will find the result of the bundling process in `./dist/`.

## SASS/SCSS? Or LESS?

You want to use SASS/SCSS or LESS to write your CSS? That's also easy. Open the file `./src/App.vue`, navigate to the `style` part. Just change the value of `lang` from `css` to `scss` or `less`.

```html
<style lang="scss">
body {
    color: #34495e;
}
h1 {
    color: #41b883;
}
</style>
```