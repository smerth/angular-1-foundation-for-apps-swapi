# Angular 1 Foundation For Apps SWAPI Viewer

This Angular 1 app is built on Foundation for Apps ( [docs](http://foundation.zurb.com/apps/docs/#!/), [code](https://github.com/zurb/foundation-apps).)

The app consumes the [SWAPI](https://swapi.co) feed for Star Wars data.

The original code is pieced together from [Smashing Magazine](https://www.smashingmagazine.com/2015/04/creating-web-app-in-foundation-for-apps/) and [xyz-angular-swapi](https://github.com/unshift-devs/xyz-angular-swapi) and [SWAPI-Wrapper](https://github.com/cfjedimaster/SWAPI-Wrapper)

![App Screenshot](https://raw.githubusercontent.com/smerth/star-wars-api-client-with-angular-and-foundation/master/screenshot.png)

## Installation

Clone this repository (and give it a new name if needed)

```bash
git clone https://github.com/smerth/angular-1-foundation-for-apps-swapi.git <new-app-name>
```

Change into the directory.

```bash
cd <new-app-name>
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

## Deploy to gh-pages

To deploy to gh-pages uncomment the line

```html
<!--<base href="/<YOUR-GITHUB-REPO-NAME>/#/" target="_blank">-->
```

then run

```bash
gulp deloy
```

To develop locally comment the line out again.

## Caveats

Currently the app only works in Chrome, due to a CORS issue on Safari and Firefox. See [this issue](http://stackoverflow.com/questions/25727306/request-header-field-access-control-allow-headers-is-not-allowed-by-access-contr) to investigate a fix.

Everything works on localhost but doesn't work on gh-pages...
