# ES6 Starter kit

Version: 3.0.0

Purpose:

Developer environment easy and fast setup.

	Tech Used: 
		webpack,
		webpack-cli, 
		@babel/core,
		babel-loader,
		@babel/preset-env: babel preset env for compiling Javascript ES6 code down to ES5,
		html-webpack-plugin,
		mini-css-extract-plugin,
		css-loader,
		webpack-dev-server,
		url-loader,
		file-loader

## Instructions:

* Webpack must be version 4.2.0

* Do: **npm install**

* Then: **npm run start**

This setup should be ready for hacking. 

* Change the favicon:

	Edit the file in **webpack.config.js**, under plugins:

	favicon: './src/images/sdlogo.ico' //your icon here

* To compile: 

	Do: **npm run build**

	That will make a dist folder with the compiled files

## Resources:

https://www.valentinog.com/blog/webpack-tutorial/