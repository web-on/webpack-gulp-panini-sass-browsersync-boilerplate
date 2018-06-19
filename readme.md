# Project template with webpack, gulp, panini, sass, browsersync, sherpa

This is a stripped-down ZURB Foundation for Sites template.

It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

To use this template, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)

### Manual Setup

To manually set up the template, first download it:

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

Finally, run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
