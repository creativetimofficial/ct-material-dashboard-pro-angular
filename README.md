# [Material Dashboard PRO Angular](https://demos.creative-tim.com/material-dashboard-pro-angular2/)

![version](https://img.shields.io/badge/version-2.7.0-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/ct-material-dashboard-pro-angular.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-material-dashboard-pro-angular/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/creativetimofficial/ct-material-dashboard-pro-angular.svg?maxAge=2592000)](https://github.com/creativetimofficial/ct-material-dashboard-pro-angular/issues?q=is%3Aissue+is%3Aclosed)

![Product Gif](https://media.giphy.com/media/fVelPn4iBLS9c3bvCt/giphy.gif)

Material Dashboard PRO Angular is a Premium Material Bootstrap 4 Admin with a fresh, new design inspired by Google's Material Design. It is based on the popular Bootstrap 4 framework and comes packed with multiple third-party plugins. All components are built to fit perfectly with each other, while aligning to the material concepts.

Material Dashboard PRO Angular makes use of light, surface and movement. The general layout resembles sheets of paper following multiple layers, so that the depth and order is obvious. Inside the archive you will find multiple example pages on how to use all components. And, of course, every element is documented.

This dashboard is the bigger version for the [Material Dashboard Angular](https://www.creative-tim.com/product/material-dashboard-angular2), which is available for free download. We have created the PRO version based on the feedback we received from people using the demo. We tried to keep it as lean as possible, but provide all the necessary tools for developing a complex product. The result is a powerful dashboard that can easily help you build admin panels, CRMs or content management systems.


Material Dashboard PRO Angular has the same line of design as the Material Kit PRO, so they go together quite good. If you think you will need more landing and example pages, be sure to check it out. If you love material design, you'll probably enjoy using these products!

You can find the Github Repo here.

#### Special thanks
During the development of this dashboard, we have used many existing resources from awesome developers. We want to thank them for providing their tools open source:
- [Robert McIntosh](https://github.com/mouse0270/bootstrap-notify) for the notification system.
- [Chartist](https://gionkunz.github.io/chartist-js/) for the wonderful charts
- [Tristan Edwards](https://twitter.com/t4t5) for the [Sweet Alert2](https://sweetalert2.github.io/)
- [Eonasdan](https://github.com/Eonasdan) for the - [DateTimPicker](https://eonasdan.github.io/bootstrap-datetimepicker/)
- Kirill Lebedev for [jVector Maps](http://jvectormap.com/)
- [Vincent Gabriel](https://twitter.com/gabrielva) for the - [Bootstrap Wizard](http://vinceg.github.io/twitter-bootstrap-wizard/)


Let us know your thoughts below. And good luck with development!

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Versions

[<img src="https://s3.amazonaws.com/creativetim_bucket/github/html.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/react.svg" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-react)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/angular.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-angular2)


| HTML | React | Angular |
| --- | --- | --- |
| [![Material Dashboard Pro HTML](https://s3.amazonaws.com/creativetim_bucket/products/51/thumb/opt_mdp_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro) | [![Material Dashboard Pro React](https://s3.amazonaws.com/creativetim_bucket/products/80/thumb/opt_mdp_react_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro-react)  | [![Material Dashboard Pro Angular](https://s3.amazonaws.com/creativetim_bucket/products/55/thumb/opt_mdp_angular_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-pro-angular2)

## Demo

- [Start page](https://demos.creative-tim.com/material-dashboard-pro-angular2/dashboard)
- [User profile page](https://demos.creative-tim.com/material-dashboard-pro-angular2/pages/user)
- [Tables page ](https://demos.creative-tim.com/material-dashboard-pro-angular2/tables/extended)
- [Maps Page](https://demos.creative-tim.com/material-dashboard-pro-angular2/maps/google)
- [Notifications page](https://demos.creative-tim.com/material-dashboard-pro-angular2/components/notifications)

[View More](https://demos.creative-tim.com/material-dashboard-pro-angular2/).



## Quick start

Quick start options:

- Buy from [Creative Tim](https://www.creative-tim.com/product/material-dashboard-pro-angular2).

## Terminal Commands

1. Install NodeJs from [NodeJs Official Page](https://nodejs.org/en).
2. Open Terminal
3. Go to your file project
4. Run in terminal: ```npm install -g @angular/cli```
5. Then: ```npm install```
6. And: ```npm start```
7. Navigate to [localhost:4200](localhost:4200)

## Documentation
The documentation for the Material Dashboard Pro Angular is hosted at our [website](https://demos.creative-tim.com/material-dashboard-pro-angular2/documentation/tutorial).

### What's included

Within the download you'll find the following directories and files:

```
material-dashboard-pro-angular
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── README.md
├── angular.json
├── documentation
│   ├── css
│   └── tutorial-components.html
├── e2e
├── karma.conf.js
├── package-lock.json
├── package.json
├── protractor.conf.js
├── src
│   ├── app
│   │   ├── app.component.html
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app.routing.ts
│   │   ├── calendar
│   │   │   ├── calendar.component.html
│   │   │   ├── calendar.component.ts
│   │   │   ├── calendar.module.ts
│   │   │   └── calendar.routing.ts
│   │   ├── charts
│   │   │   ├── charts.component.html
│   │   │   ├── charts.component.ts
│   │   │   ├── charts.module.ts
│   │   │   └── charts.routing.ts
│   │   ├── components
│   │   │   ├── buttons
│   │   │   │   ├── buttons.component.html
│   │   │   │   └── buttons.component.ts
│   │   │   ├── components.module.ts
│   │   │   ├── components.routing.ts
│   │   │   ├── grid
│   │   │   │   ├── grid.component.html
│   │   │   │   └── grid.component.ts
│   │   │   ├── icons
│   │   │   │   ├── icons.component.html
│   │   │   │   └── icons.component.ts
│   │   │   ├── notifications
│   │   │   │   ├── notifications.component.html
│   │   │   │   └── notifications.component.ts
│   │   │   ├── panels
│   │   │   │   ├── panels.component.html
│   │   │   │   └── panels.component.ts
│   │   │   ├── sweetalert
│   │   │   │   ├── sweetalert.component.html
│   │   │   │   └── sweetalert.component.ts
│   │   │   └── typography
│   │   │       ├── typography.component.html
│   │   │       └── typography.component.ts
│   │   ├── dashboard
│   │   │   ├── dashboard.component.html
│   │   │   ├── dashboard.component.ts
│   │   │   ├── dashboard.module.ts
│   │   │   └── dashboard.routing.ts
│   │   ├── forms
│   │   │   ├── extendedforms
│   │   │   │   ├── extendedforms.component.html
│   │   │   │   └── extendedforms.component.ts
│   │   │   ├── forms.module.ts
│   │   │   ├── forms.routing.ts
│   │   │   ├── regularforms
│   │   │   │   ├── regularforms.component.html
│   │   │   │   └── regularforms.component.ts
│   │   │   ├── validationforms
│   │   │   │   ├── field-error-display
│   │   │   │   │   ├── field-error-display.component.css
│   │   │   │   │   ├── field-error-display.component.html
│   │   │   │   │   └── field-error-display.component.ts
│   │   │   │   ├── password-validator.component.ts
│   │   │   │   ├── validationforms.component.html
│   │   │   │   └── validationforms.component.ts
│   │   │   └── wizard
│   │   │       ├── wizard.component.css
│   │   │       ├── wizard.component.html
│   │   │       └── wizard.component.ts
│   │   ├── layouts
│   │   │   ├── admin
│   │   │   │   ├── admin-layout.component.html
│   │   │   │   └── admin-layout.component.ts
│   │   │   └── auth
│   │   │       ├── auth-layout.component.html
│   │   │       └── auth-layout.component.ts
│   │   ├── main.ts
│   │   ├── maps
│   │   │   ├── fullscreenmap
│   │   │   │   ├── fullscreenmap.component.html
│   │   │   │   └── fullscreenmap.component.ts
│   │   │   ├── googlemaps
│   │   │   │   ├── googlemaps.component.html
│   │   │   │   └── googlemaps.component.ts
│   │   │   ├── maps.module.ts
│   │   │   ├── maps.routing.ts
│   │   │   └── vectormaps
│   │   │       ├── vectormaps.component.html
│   │   │       └── vectormaps.component.ts
│   │   ├── md
│   │   │   ├── md-chart
│   │   │   │   ├── md-chart.component.css
│   │   │   │   ├── md-chart.component.html
│   │   │   │   ├── md-chart.component.spec.ts
│   │   │   │   └── md-chart.component.ts
│   │   │   ├── md-table
│   │   │   │   ├── md-table.component.html
│   │   │   │   └── md-table.component.ts
│   │   │   └── md.module.ts
│   │   ├── pages
│   │   │   ├── lock
│   │   │   │   ├── lock.component.html
│   │   │   │   └── lock.component.ts
│   │   │   ├── login
│   │   │   │   ├── login.component.html
│   │   │   │   └── login.component.ts
│   │   │   ├── pages.module.ts
│   │   │   ├── pages.routing.ts
│   │   │   ├── pricing
│   │   │   │   ├── pricing.component.html
│   │   │   │   └── pricing.component.ts
│   │   │   └── register
│   │   │       ├── register.component.html
│   │   │       └── register.component.ts
│   │   ├── shared
│   │   │   ├── fixedplugin
│   │   │   │   ├── fixedplugin.component.css
│   │   │   │   ├── fixedplugin.component.html
│   │   │   │   ├── fixedplugin.component.spec.ts
│   │   │   │   ├── fixedplugin.component.ts
│   │   │   │   └── fixedplugin.module.ts
│   │   │   ├── footer
│   │   │   │   ├── footer.component.html
│   │   │   │   ├── footer.component.ts
│   │   │   │   └── footer.module.ts
│   │   │   └── navbar
│   │   │       ├── navbar.component.html
│   │   │       ├── navbar.component.ts
│   │   │       └── navbar.module.ts
│   │   ├── sidebar
│   │   │   ├── sidebar.component.html
│   │   │   ├── sidebar.component.ts
│   │   │   └── sidebar.module.ts
│   │   ├── tables
│   │   │   ├── datatable.net
│   │   │   │   ├── datatable.component.html
│   │   │   │   └── datatable.component.ts
│   │   │   ├── extendedtable
│   │   │   │   ├── extendedtable.component.html
│   │   │   │   └── extendedtable.component.ts
│   │   │   ├── regulartable
│   │   │   │   ├── regulartable.component.html
│   │   │   │   └── regulartable.component.ts
│   │   │   ├── tables.module.ts
│   │   │   └── tables.routing.ts
│   │   ├── timeline
│   │   │   ├── timeline.component.html
│   │   │   ├── timeline.component.ts
│   │   │   ├── timeline.module.ts
│   │   │   └── timeline.routing.ts
│   │   ├── userpage
│   │   │   ├── user.component.html
│   │   │   ├── user.component.ts
│   │   │   ├── user.module.ts
│   │   │   └── user.routing.ts
│   │   └── widgets
│   │       ├── widgets.component.html
│   │       ├── widgets.component.ts
│   │       ├── widgets.module.ts
│   │       └── widgets.routing.ts
│   ├── assets
│   │   ├── img
│   │   └── scss
│   │       ├── core
│   │       ├── dashboard
│   │       ├── plugins
│   │       └── material-dashboard.scss
│   ├── environments
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.css
│   ├── test.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.spec.json
│   └── typings.d.ts
├── tsconfig.json
├── tslint.json
├── typings
└── typings.json
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Resources
- [Live Preview](https://demos.creative-tim.com/material-dashboard-pro-angular2/)
- Buy Page: https://www.creative-tim.com/product/material-dashboard-pro-angular2
- Documentation is [here](https://demos.creative-tim.com/material-dashboard-pro-angular2/documentation/tutorial)
- License Agreement: https://www.creative-tim.com/license
- Support: https://www.creative-tim.com/contact-us
- Issues: [Github Issues Page](https://github.com/creativetimofficial/ct-material-dashboard-pro-angular/issues)
- Material Dashboard Angular - [demo](https://www.creative-tim.com/product/material-dashboard-angular2?ref=github-mda-pro)
- For Front End Development - [Material Kit Pro ](https://www.creative-tim.com/product/material-kit-pro?ref=github-mda-pro)

## Reporting Issues
We use GitHub Issues as the official bug tracker for the Material Dashboard Pro Angular. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Dashboard Pro Angular. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://www.creative-tim.com/contact-us) instead of opening an issue.

## Licensing

- Copyright 2018 Creative Tim (https://www.creative-tim.com)
- Creative Tim [license](https://www.creative-tim.com/license)

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes/angular-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)

##### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Google+: <https://plus.google.com/+CreativetimPage>

Instagram: <https://instagram.com/creativetimofficial>
