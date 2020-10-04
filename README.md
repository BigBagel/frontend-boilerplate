# Frontend Boilerplate (Gulp + Webpack + Panini)

Boilerplate I use for static HTML sites. Config for most things can be found in [gulp/config.js](gulp/config.js).

Uses:
- [Gulp](https://gulpjs.com/) as the overall build system
- [Webpack](https://webpack.js.org/) for JS
- [Sass](https://sass-lang.com/) and [PostCSS](https://postcss.org/) for CSS
- [Panini](https://github.com/foundation/panini) (Handlebars for lazy people) for templating
- [Browsersync](https://browsersync.io/) for live reloading
- [imagemin](https://github.com/imagemin/imagemin) for image...min-ing

## Quickstart
1. Install [Node.js](https://nodejs.org/) (if needed)
2. Clone or download the repo
4. From within the project's directory, run `npm install`
5. Use `npm run dev` to start up a local server and watch for file changes
6. Use `npm run build` to complie everything for production 