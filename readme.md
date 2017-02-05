<a align="center" href="http://getbootstrap.com/"><img width="100%" src="http://blog.getbootstrap.com/img/2015/bs4-alpha.png" alt="bootstrap"></a>

> A boilerplate project based on Bootstrap framework

## What is it exactly?

It offers a starting project with Gulp, Bootstrap, Pug, Stylus and CoffeeScript. 

## Download in your workspace

```sh
$ git clone https://github.com/frontend-starter/bootstrap.git
```

## Rename and go into your project

```sh
$ mv bootstrap my-project
$ cd my-project
```

## Install the dependencies and let Gulp do the job

```sh
$ npm start
```

## Go to work!

Gulp puts your assets in a src/assets directory and generates an index.html file.
When everything is in place, your browser should display the sample page. Whenever you
modify a .pug, .styl or .coffee file, the browser reloads automatically.

## Production

```sh
$ gulp build
```

When your satisfied, Gulp builds everything you need for production (optimized images, minified 
and concatenated files).

## Make it yours

Feel free to add, remove, change things at your convenience!

## Available commands

- `gulp serve` - starts the development server with Browersync enabled

- `gulp build` - generates the distribution files

## License

Designed with ♥ by [Sébastien Pereda](https://github.com/bastosh). Licensed under the MIT License.
