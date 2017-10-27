## About
------
This is my personal website. It displays the projects that I work on as a web developer and my contact information. This website was one of the first projects in my Front-End Web Development Nanodegree at Udacity.

### Features
------
- The website is fully responsive and works on mobile, tablet, and desktop devices.
- Uses Sass to help write modular CSS.
- Uses Gulp to improve workflow, optimize assets, compile and minify CSS, and minify HTML.

### Getting Started
------
To view the website, go to [https://leasak.github.io/](https://leasak.github.io/) in your browser to see a live version.

You can also download the project files via [gitHub](https://github.com/LeaSak/leasak.github.io.git) or via the command line:

```sh
git clone https://github.com/LeaSak/leasak.github.io.git
```

Navigate to the project directory, and open **index.html** in your browser.

All development files are located in the **src** directory.

If you wish to build the project, see below.

### Build
------
To build the app, you first need to set-up your development environment.

#### Step 1: Install node.js, npm, Gulp, and Bower
Make sure you have **node.js**, **npm**, **gulp**, and **bower** installed. For instructions on how to install these consult the following links: [node](https://nodejs.org/en/), [npm](https://docs.npmjs.com/getting-started/installing-node), [gulp.js](http://gulpjs.com/), [bower.js](https://bower.io/)
*Note*: You do not need to create `package.json` and `gulpfile.js` files.

#### Step 2: Install Gulp Dependencies
Make sure you're in the project directory.
To install the **Gulp** dependencies, run:
```sh
$ npm install
```
You should now find these plugins in your **node_modules** folder.

#### Step 3: Install Bower Dependencies
Make sure you're in the project directory. Now we'll install the project's development dependencies.
To install **Bower** dependencies, run:
```sh
$ bower install
```
You should now find the bower packages in the **bower_components** folder.

#### Step 4: Build
To simply build the site, run the following command within your project directory:
```sh
$ gulp build
```
If you want to make changes to the project, run the default gulp task:
```sh
$ gulp
```
The default gulp task includes watch tasks, so when you make any changes to the files in the **src** directory, the site will be rebuilt again and your changes will be implemented. You'll need to refresh the browser to see your changes.
For more information, please inspect **gulpfile.js**

*Note*: The gulp plugin **gulp-responsive** uses the library **Sharp**. You need to have **Sharp** installed for this plugin to work. See [this link](http://sharp.dimens.io/en/stable/install/) for instructions. Also, this project was built using **Sass**. To edit the stylesheets, edit the files found in the **src/scss/** directory. Do not edit the css output files found in the **css/** directory. For more information on **Sass**, visit [Sass](http://sass-lang.com/).

#### Step 4: Inspect
Open **index.html** in your browser.

## Feedback
Feedback is very welcome. Please contact me via [email](leaann.sakmann@gmail.com).
