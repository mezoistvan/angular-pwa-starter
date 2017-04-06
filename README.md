# ng2-pwa-starter
Lightweight starter 'ng new' with added app shell features (sw-toolbox, sw-precache, web app manifest) and server-side rendering (angular-universal).

Based on the excellent article by Houssein Djirdeh available here: https://houssein.me/progressive-angular-applications. Check out his working PWA for hackernews here: https://github.com/housseindjirdeh/angular2-hn. Huge kudos!

```
@angular/cli v1.0.0
@angular/core v4.0.1
```

4+ versions of Angular are likely to incorporate all of these features. Until then, this is intended to be an upgraded `ng new <project-name>`.

This is without `ng eject`! Ejecting the webpack config provides with much deeper customisation, but that is not the scope of this starter kit.

```
# ng -v
    _                      _                 ____ _     ___
   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
  / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
 / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
/_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
               |___/
@angular/cli: 1.0.0
node: 7.7.0
os: win32 x64
@angular/common: 4.0.1
@angular/compiler: 4.0.1
@angular/core: 4.0.1
@angular/forms: 4.0.1
@angular/http: 4.0.1
@angular/platform-browser: 4.0.1
@angular/platform-browser-dynamic: 4.0.1
@angular/router: 4.0.1
@angular/cli: 1.0.0
@angular/compiler-cli: 4.0.1
```

## 100/100 PWA Lighthouse rating when deployed to Firebase

![alt tag](https://raw.githubusercontent.com/mezoistvan/angular-pwa-starter/master/src/assets/lighthouse/lighthouse.png)

```
npm run build
```
