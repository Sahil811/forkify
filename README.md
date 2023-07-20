# forkify

Here is a draft README.md for a Forkify app repository:

# Forkify Recipe App

This is a recipe application with custom recipe uploads and bookmarks. Built with JavaScript, forkify allows you to search for recipes, view details, add ingredients to a shopping list, and manage your own recipes and bookmarks.

## Features

- Search and view recipe details 
- Add ingredients to shopping list
- Create, edit, and manage your own recipes
- Bookmark recipes for later reference
- Mobile friendly responsive design
- Uses [Forkify API](https://forkify-api.herokuapp.com/v2)

## Usage

To run locally:

1. Clone this repo
2. Install dependencies  
`npm install`
3. Start local dev server  
`npm start`
4. Open your browser to [http://localhost:1234](http://localhost:1234)

## Customizing

The main application JavaScript is located in `src/js/`.

Stylesheets are located in `src/sass/` and use SCSS.

The dev server uses [webpack-dev-server](https://github.com/webpack/webpack-dev-server) and [Babel](https://babeljs.io/) for ES6 and module bundling. Configuration can be found in `webpack.config.js`. 

## Building for Production

Run `npm run build` to compile assets with webpack into `/dist` folder.

## API

Forkify uses the [Forkify API](https://forkify-api.herokuapp.com/v2) for recipe data. You'll need to register for a free API key and add it to `config.js`.

API documentation can be found on the [Forkify docs site](https://forkify-api.herokuapp.com/v2).

## License

This project is open source and available under the [MIT License](LICENSE).
