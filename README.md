# SbS
Prepare folders
~~~
git init
npm init
mkdir public
touch public\index.html
mkdir src
~~~

Install and configure Javascript base dependencies
~~~
npm install --save-dev @babel/core@7.12.10 @babel/cli@7.12.10 @babel/preset-env@7.12.10 @babel/preset-react@7.12.10
touch .babelrc
npm install --save-dev webpack@4.19.1 webpack-cli@3.1.1 style-loader@1.2.1 css-loader@3.6.0 babel-loader@8.0.2
npm i -g webpack-dev-server@3.11.0
touch webpack.config.js
~~~

Install React
~~~
npm install react@17.0.1 react-dom@17.0.1
webpack-dev-server --mode development
~~~