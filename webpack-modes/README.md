# ****** INSTRUCTIONS ******

mkdir webpack-modes && cd $_

npm init -y

npm i -D webpack webpack-cli

npm i -D babel-core babel-preset-env babel-loader

# https://github.com/babel/babel-loader

# webpack 4.x | babel-loader 8.x | babel 7.x

npm install -D babel-loader @babel/core @babel/preset-env webpack

# webpack 4.x | babel-loader 7.x | babel 6.x

npm install -D babel-loader@7 babel-core babel-preset-env webpack

npm i -D html-webpack-plugin