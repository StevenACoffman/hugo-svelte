# Hugo-Svelte app

This is a project template for [Svelte](https://svelte.dev) and [Hugo](https://gohugo.io) apps. It lives at https://gitlab.com/datwood/hugo-svelte.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit git@gitlab.com:datwood/hugo-svelte.git hugo-svelte
cd hugo-svelte
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*

****
## Get started

Install the dependencies...

```bash
cd hugo-svelte
npm install
```

...then start [Rollup](https://rollupjs.org) and Hugo:

```bash
npm run dev
```

Navigate to [localhost:1313](http://localhost:1313). You should see your app running. Edit a component file in `svelte` and save it. Livereload is built-in.

## Building

From within your project folder:

```bash
npm run build
```

You will find your website files inside `public/`.
