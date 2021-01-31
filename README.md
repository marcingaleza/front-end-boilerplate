# Front-end Boilerplate

This is a very simple boilerplate which uses NPM task to build and compile Tailwind CSS, and also to optimize SVG and raster images. The image optimization part was inspired by [this repository](https://github.com/cferdinandi/build-tool-boilerplate).

## Get started

1. First you need to make sure you have [Node.js](http://nodejs.org/).
2. Download this repository.s
3. Review `package.json` to see if you need all tasks.
4. Run `npm install`.

## NPM Tasks

```
npm run clear     # clear /dist directory
npm copy copy     # copy files from src/content to dist directory (usually usless task, just for testing Tailwind CSS)
npm run css:dev   # compile a full version of Tailwind CSS (use for developing)
npm run css:prod  # compile a purged version of Tailwind CSS (adjust tailwind.config.js for proper purge directory)
npm run svg       # optimize SVG files with SVGO
npm run img       # optimize PNG and JPG files with Imagemin
npm run assets    # running assets tasks
npm run dev       # running assets tasks + compiling a full version of Tailwind CSS
npm run build     # running assets tasks + compiling purged version of Tailwind CSS
```
