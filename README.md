# Gulp Boilerplate

My base files to run gulp in projects.

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)

```sh
# Clone this repository
$ git clone git@github.com:brenopolanski/gulp-boilerplate.git
$ cd my-project

# install dependencies
$ npm install
# run tasks and serve
$ gulp
```

### Tasks

- `gulp`: Initialize watch for changes and a server (localhost:3000);
- `gulp js`: Execute js files;
- `gulp stylus`: Compile stylus files;
- `gulp imagemin`: Compress image files;
- `gulp watch`: Call for watch files;
- `gulp jade`: Compile jade files;
- `gulp deploy-pages`: Deploy compiled files at `build` to `github` on branch `gh-pages`.

## Contributing

If you want to help, please read the [Contributing](https://github.com/brenopolanski/gulp-boilerplate/blob/master/CONTRIBUTING.md) guide.

## History

For detailed changelog, see [Releases](https://github.com/brenopolanski/gulp-boilerplate/releases).

## License

[MIT License](http://brenopolanski.mit-license.org/) © Breno Polanski
