angular-ionic-requirejs-phonegap-seed
=====================================

Sample PhoneGap / Cordova application built with Angular and Ionic Framework, uses RequireJS for loading scripts. Example controllers, filters, services, directives and config.

Forked from ionic seed (https://github.com/driftyco/ionic-angular-cordova-seed) and other seed projects.

#Attention : if you want to use "window.name = "NG_DEFER_BOOTSTRAP!"; " and resumeBootstrap() to run the angular,please mind: 
  1.modification has been made in www/js/routes line 18, which enable the application to resume to run correctly;
  2.add the window.name = "NG_DEFER_BOOTSTRAP!"; to the main.js
