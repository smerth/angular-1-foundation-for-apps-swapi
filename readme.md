

# Foundation for Apps Template

[![devDependency Status](https://david-dm.org/zurb/foundation-apps-template/dev-status.svg)](https://david-dm.org/zurb/foundation-apps-template#info=devDependencies)

This is the default template project for Foundation for Apps, powered by Gulp, Angular, and libsass. It provides you with a basic template to get started with Foundation for Apps and Angular.

If you're already an Angular developer, you may instead want to install the components into your own stack using Bower: `bower install foundation-apps`

## Requirements

You'll need the following software installed to get started.

  - [Node.js](http://nodejs.org): Use the installer for your OS.
  - [Git](http://git-scm.com/downloads): Use the installer for your OS.
    - Windows users can also try [Git for Windows](http://git-for-windows.github.io/).
  - [Gulp](http://gulpjs.com/) and [Bower](http://bower.io): Run `npm install -g gulp bower`
    - Depending on how Node is configured on your machine, you may need to run `sudo npm install -g gulp bower` instead, if you get an error with the first command.

## Get Started

Clone this repository, where `app` is the name of your app.

```bash
git clone https://github.com/zurb/foundation-apps-template.git app
```

Change into the directory.

```bash
cd app
```

Install the dependencies. If you're running Mac OS or Linux, you may need to run `sudo npm install` instead, depending on how your machine is configured.

```bash
npm install && bower install
```

To run the compiling process once, without watching any files, use the `build` command.

```bash
npm run build
```

To serve the site and watch for changes during development

```bash
npm start
```

Problem with gh-pages

For debugging:

```bash
npm start build && git add . && git commit -m "debugging gh-pages issues" && git push && gulp deploy && npm start
```

