# WebGameStub

WebGameStub helps you get a quick and easy start on writing an HTML5 game with 2D canvas with a simple template and a few tools.
It offers a good starting point for the game itself and smoothes off a variety of the rough edges associated with writing and publishing a Web app.

WebGameStub is about saving you time and effort so that you can focus on writing your game.
It's about not having to write the most basic game infrastructure pieces, like canvas setup and an update/render loop.
It's about having an easier starting point than a blank canvas.
It's about not having to spend your time stitching together the usual cross-browser bits associated with bootstrapping an app on the web.

WebGameStub is not a framework but rather a collection of files that help you
get your project started quickly with some best practices. With the notable
exception of require.js, pretty much anything in the www/ directory can be
deleted if desired.

### What WebGameStub Gets You

* A simple update/render loop and canvas.
* A version of Lost Decade's simple canvas game that you can inspect and extend.
* Links to helpful game docs, API docs, and open art resources so you don't have to hunt for them.
* HTML & CSS based on HTML5 Boilerplate for speed, robustness, and futureproofing.
* (Optional) Requires node.js: webserver for HTTP testing, play your game as a
    native app, automated optimization, deployment to github pages, and library
    installation using volo.

## Getting Started

1. [Download](https://github.com/mozilla/WebGameStub/zipball/develop) the current version of WebGameStub
2. Review index.html and app.js in examples/simple_canvas_game. These are the main parts of the simple canvas game built on top of WebGameStub
    * Depending on your level of experience you may find Lost Decade's [excellent tutorial](http://www.lostdecadegames.com/how-to-make-a-simple-html5-canvas-game/) helpful when going through the code
3. Use index.html and app.js in the www and www/js folders as a starting point for your own game
    * Many of the additional files in WebGameStub come from HTML5 Boilerplate, which has [Docs](http://html5boilerplate.com/docs/#the-core-of-html5-boilerplate) you can read to learn more
4. Once you've made some changes you can add all of your files to a new git repository.
Navigate to your project folder in a terminal and do the following commands:

        > git init
        > git add -A
        > git commit -m "Initial commit"

# Helpful Tools (requires node.js)

## Tool Prerequisites

* Be sure that [node.js and npm](http://nodejs.org/) (>= 0.6) are installed and in your PATH
* (optional) If you wish to deploy to github pages, ensure that
 [git](http://help.github.com/set-up-git-redirect) is installed and configured
* Use npm to install volo into your path, if it's not there already:

    > sudo npm install -g volo

Windows users will need to drop the sudo from this command

## Easy Testing Over HTTP 

Things sometimes work differently when browsed to via file: URLs.  Test over
HTTP for more accurate results:

    > volo serve
    [1] 11563
    > starting web server on port 8086
    
Now pointing your browser to http://localhost:8086/ will serve up your files
for testing.

## Simple Library Installation

Right now there is a small (but growing) number of libraries useful to games that install out-of-the-box using volo. You can see a list of them [here](https://github.com/mozilla/WebGameStub/wiki/game-library-volo-compatibility), along with some information about what to do if you encounter problems.

    > volo add three.js
    Using github repo "mrdoob/three.js" for "three.js"...
    Downloading: https://raw.github.com/mrdoob/three.js/master/build/Three.js
    Installed github:mrdoob/three.js/master at js/three.js

    > volo add stats.js
    Using github repo "mrdoob/stats.js" for "stats.js"...
    Downloading: https://raw.github.com/mrdoob/stats.js/master/build/Stats.js
    Installed github:mrdoob/stats.js/master at www/js/lib/stats.js

## Optimize for high performance

Build a minified version:

    > volo build
    (...)

## Deploy to github pages

Deploy the built version to the gh-pages branch of suitably named repo:

    > volo ghdeploy
    Log in to GitHub to complete action (your password is not saved. It is sent over SSL to GitHub and converted to an OAuth token)
    GitHub user name: dmose
    GitHub password:
    Contacting GitHub...
      (...)
    To git@github.com:dmose/monkeyGame.git
    e5dbfd4..1296c81  gh-pages -> gh-pages
    GitHub Pages is set up. Check http://dmose.github.com/monkeyGame/ in about 10-15 minutes.

## Make Your Game Playable as an App

* Build and deploy to github pages, as above
* Using Firefox 16 (currently available as the Nightly channel), browse to 
    the install page (for example,
    <http://dmose.github.com/WebGameStub/install.html>)
* When prompted, click the "Install" button.
* Look in your OS application list (on Mac OS X, for example, this is the global Applications folder)
* Click on the app (from the above example, named Simple Canvas Game) to launch

# More Resources

## Game APIs

* [Pointer Lock API](https://developer.mozilla.org/en/API/Pointer_Lock_API)
* [Fullscreen API](https://developer.mozilla.org/en/DOM/Using_full-screen_mode)

## 2D Art

* [Danc's Miraculously Flexible Game Prototyping Tiles](http://www.lostgarden.com/2007/05/dancs-miraculously-flexible-game.html) (see bottom of post for download link)
* [Open Game Art 2D Art](http://opengameart.org/art-search-advanced?keys=&field_art_type_tid[]=9&field_art_tags_tid_op=and&field_art_tags_tid=&name=&sort_by=count&sort_order=DESC&Collection=)

If you know of any other good sources of free reusable art please let us know by
filing a [github issue](https://github.com/mozilla/WebGameStub/issues)

## Miscellaneous

* [WebGameStub's Github repo](https://github.com/mozilla/WebGameStub/)
* [Frequently Asked Questions](https://github.com/mozilla/WebGameStub/wiki/Frequently-Asked-Questions), including info about what this means for the Minimalist Template
* Lost Decade's [excellent tutorial](http://www.lostdecadegames.com/how-to-make-a-simple-html5-canvas-game/) on how they built the  simple canvas game
* [HTML5 Boilerplate](http://html5boilerplate.com/)

# Feedback and helping out

If you run into something that's missing or that is getting in your way when using WebGameStub, please help us out by opening a [github issue](https://github.com/mozilla/WebGameStub/issues) (or even a pull request!) to discuss it.
We're often available in [#games on irc.mozilla.org](irc://irc.mozilla.org/#games) for questions.
