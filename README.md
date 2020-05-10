# Angular Electron Seed Barebones

This project is a super barebones angular project with electron. It is a regular angular 9 app whit electron and event package it !

![Website Build](https://github.com/Mrgove10/angular-electron-minimal/workflows/Website%20Build/badge.svg)
![Application Build](https://github.com/Mrgove10/angular-electron-minimal/workflows/Application%20Build/badge.svg)

![](https://angular.io/assets/images/logos/angular/angular.png =250x250) ![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Electron_Software_Framework_Logo.svg/1200px-Electron_Software_Framework_Logo.svg.png =250x250)

The stack :

- Angular 9.1 ([link](https://angular.io/))
- Electron 8.2 ([link](https://www.electronjs.org/))
- Electron Builder 22.6 ([link](https://www.electron.build/))

- [Angular Electron Seed Barebones](#angular-electron-seed-barebones)
  - [Developpement](#developpement)
    - [Website](#website)
    - [Application](#application)
  - [Building for production](#building-for-production)
    - [Website](#website-1)
    - [Application](#application-1)

## Developpement

When possible you whould be developping in website mode. You will get hot reload and faster compiles times.

### Website

You can test and developpe your app as a website with ```$ npm run start``` then navigating to http://localhost:4200/

To do a test build you can run ```$ npm run build```

### Application

To test in electron ```$ npm run electron```

## Building for production

### Website

If you want to export your app as a website you sure can !

You can run ```$ npm run build:prod``` to do that, it will be exported to `/dist`

### Application

To build for the current platform you can run ```$ npm run electron:build```
To build for every platform you can run ```$ npm run electron:build:all```

the output app should be in the `/release` directory
