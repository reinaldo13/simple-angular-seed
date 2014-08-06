# simple-angular-seed — a very basic and simple seed for AngularJS apps

This project is an application skeleton for a typical [AngularJS](http://angularjs.org/) web app.
You can use it to quickly start your angular webapp projects.

The seed contains a sample AngularJS application. It is all HTML, JS and CSS. It doesn't install anything else in your dev environment, so no dependencies! I did this on purpose so you have control over your web server, test and dev tools, etc.

The seed app doesn't do much, just shows how to wire two controllers and views together.

## Getting Started

To get you started you can simply clone the angular-seed repository and install the dependencies:

### Prerequisites

You need git to clone the simple-angular-seed repository. You can get it from
[http://git-scm.com/](http://git-scm.com/).

### Clone angular-seed

Clone the angular-seed repository using [git][git]:

```
git clone https://github.com/reinaldo13/simple-angular-seed.git
cd simple-angular-seed
```

### Run the Application

Coming soon!



## Directory Layout

    app/                --> all of the files to be used in production
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      index.html        --> app layout file (the main html template file of the app)
      js/               --> javascript files
        app.js          --> application
        controllers.js  --> application controllers
        directives.js   --> application directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
      partials/             --> angular view partials (partial html templates)
        partial1.html
        partial2.html

    test/               --> test config and source files (you choose the test framework)

## Serving the Application Files

While angular is client-side-only technology and it's possible to create angular webapps that
don't require a backend server at all, I recommend serving the project files using a local
webserver during development to avoid issues with security restrictions (sandbox) in browsers. The
sandbox implementation varies between browsers, but quite often prevents things like cookies, xhr,
etc to function properly when an html page is opened via `file://` scheme instead of `http://`.

## Contact

For more information on AngularJS please check out http://angularjs.org/
