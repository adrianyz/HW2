# HW2

Build a Node-based video app in the Authoring class, using queries
and database assets that you’ll be compiling the Advanced Web class.


## Project Requirement

* Use the assets you’re creating for the Roku Flashback app for Electronic Image & Production to create the views and templates you will be working with.

* The first part of the project (fall term) will focus on creating the correct app structure with some tooling in place (Grunt, SASS etc).

* Continue to develop the app with various features in the winter term.

* A user should be able to log in, filter and select a movie, tv show or audio based on user profile (adult or kids).

* Build an API that will let a user comment on the selection, rate it, and share via social media.

* Build a chat application as part of the app to communicate with other users in real time.

### Installing

* Preparing a new Grunt project:

A typical setup will involve adding two files to your project: package.json and the Gruntfile.

package.json: This file is used by npm to store metadata for projects published as npm modules. You will list grunt and the Grunt plugins your project needs as devDependencies in this file.

Gruntfile: This file is named Gruntfile.js or Gruntfile.coffee and is used to configure or define tasks and load Grunt plugins. When this documentation mentions a Gruntfile it is talking about a file, which is either a Gruntfile.js or a Gruntfile.coffee.


This will install the latest version of Grunt in your project folder, adding it to your devDependencies:

```
npm install grunt --save-dev
```

The same can be done for gruntplugins and other node modules. As seen in the following example installing the uglify task module:
```
npm install grunt-contrib-uglify --save-dev
```

Install  SASS
```
npm install grunt-contrib-sass --save-dev
```
