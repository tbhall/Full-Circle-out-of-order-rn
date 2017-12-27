# Angular NativeScript Seed

Build truly web and native applications using NativeScript and Angular. This seed allows your project to share code between the environments; having complete control over dependencies.

## Highlights
- i18n Translations
- Lazy Loaded Modules
- Angular CLI // Webpack // Testing
- Target Phone and Tablet Templates Individually. The following extensions are supported:

Extension                        | Platform
-------------------------------- | -----------
`.{html/scss}`                   | Recommended for Web. Does apply to both platforms when **.tns** equivalent does not exist.
`.tns.{html/scss}`               | Only for mobile
`.tns.ios.{html/scss}`           | Only for iOS
`.tns.android.{html/scss}`       | Only for Android
`.tns.ios.phone.{html/scss}`     | Only for iOS Phone
`.tns.android.phone.{html/scss}` | Only for Android Phone
- Docker build provided using NGINX to serve web content and load balance reverse proxied backends. (See nginx folder for setup instructions)

## Getting Started

Web is setup from the root.

```
npm i
```

Mobile is setup from the `nativescript` folder.

```
cd nativescript
npm i
```

Each platform is run respective to it's folder. View available commands here:

- [Seed Commands](https://github.com/TeamMaestro/angular-native-seed/wiki/Seed-Commands)

## How To's
- [Integrating Angular Material (`@angular/material`)](https://github.com/TeamMaestro/angular-native-seed/wiki/Integrating-Material-for-Web)
- [Integrating Ionic Styles & Components - Demo Project @proyecto26](https://github.com/proyecto26/nativescript-ionic-template)
- [NativeScript with Angular Web Application Conversion](https://nativescripting.com/course/nativescript-with-angular-web-application-conversion)
