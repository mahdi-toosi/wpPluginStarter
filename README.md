# WordPress Plugin Starter

A WordPress starter plugin with required tool belts 😎

## 📦 What it ships with?

-   Pre-configured vite config
    -   Babel loader, Vue loader
    -   Uglify JS for production
    -   Separate `frontend.js` and `admin.js`
    -   Extracted CSS to separate `frontend.css` and `admin.css` files.
    -   Auto reloading with Browser with **Browsersync** _([config](config.json))_
-   [Vue](https://vuejs.org/) and [Vue Router](https://router.vuejs.org/en/)
-   Frontend (shortcode) and Backend starter app
-   Modern PHP codebase with [namespace](http://php.net/manual/en/language.namespaces.php) support

## 🚚 Running

1. Clone this repository in your plugins folder
1. Activate the plugin

## 👨‍💻 Post Installation

1. The name of the plugin class is `Base_Plugin`, change the class name with your desired class name.
1. Replace the PHP namespace `App` with your desired name.
1. Replace `wpPluginStarter` or `WP_PLUGIN_STARTE` reference in files.
1. Run `yarn install`
1. To start developing, run `npm run dev` 🤘
1. For production build, run `npm run build` 👍

## About

Made by [mahdi Toosi](https://github.com/mahdi-toosi).

_Found anything that can be improved? You are welcome to contribute._
