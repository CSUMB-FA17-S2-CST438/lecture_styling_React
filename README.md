# Styling the React code

This repo presents the React styling for CST438.

## Upgrade Node version to 6

```$ nvm install 6```

## Installing Webpack globally

This line installs Webpack on your Cloud9 workspace, kind of like how you might
install from a package or `brew install` something.

```$ npm install -g webpack```

## Installing `npm` dependencies from `package.json`

This line starts up `npm`, which looks inside `package.json`, gets a list of
packages, and installs them to the `node_modules` folder inside your repository.

```$ npm install```

## Compiling Javascript using Webpack

This line starts up Webpack, which looks inside `webpack.config.js`, loads
configuration options, and starts transpiling your JS code into `static/script.js`.

```$ webpack --watch```

(The program should not stop running. Leave it running.)

## Run the web app

Run `app.py` and verify that the React renders. Click on "Send up a random
number!". The page should interactively update.

## Figure out how the styling happens

* `static/style.css` has all of the styles used
* The HTML for this is generated by React, in `Content.js`.
