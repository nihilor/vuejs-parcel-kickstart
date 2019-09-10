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

## LICENSE

MIT License

Copyright (c) 2019 Mark Lubkowitz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.