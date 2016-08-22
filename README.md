# Piktor
A Lektor theme based on Pixyll

A simple and elegant theme for using with [Lektor](http://getlektor.com/).

![Screen](/screens/screen_md.png?raw=true "Screenshot")

![Screen](/screens/screen.png?raw=true "Screenshot")

Please follow the steps on [installation here.](https://www.getlektor.com/docs/installation/)

Install Lektor for your operating System as per the steps given.

For enabling webpack support

* Install node
* Make sure npm is on your path
* Run the following command  
```
$ npm install --save-dev webpack babel-core node-sass babel-loader sass-loader css-loader url-loader style-loader file-loader
```
* Then to generate your site
```
lektor server -f webpack
```
(or)
* To build the site
 ```
lektor build -f webpack
```

For you own site. Modify the config file in /configs/google-analytics.ini to include your google analytic id.

This is a port of Pixyll. Not all functionalities are ported.
