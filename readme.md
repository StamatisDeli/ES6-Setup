ES6 Starter kit

Version: 2.0.0

Purpose: developer environment easy and fast setup
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

Do: nmp install

Then: npm run start

This setup should be ready for hacking. 

To change the favicon, change the path in webpack.config, under plugins

To compile: npm run build
That will make a dist folder with the compiled files