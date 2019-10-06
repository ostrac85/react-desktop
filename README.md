# react-desktop 
https://itnext.io/create-desktop-with-electron-react-and-c-86f9765809b7

Before starting the coding part follow the steps below:


1. npm init --yes
2. npm i -D electron
3. npm i -D typescript
4. npm i -D tslint
5. npm i -D prettier

web pack
1. npm i -D webpack webpack-cli
2. npm i -D html-webpack-plugin
3. npm i -D @babel/cli @babel/core @babel/preset-env babel-loader @babel/plugin-proposal-class-properties @babel/plugin-transform-arrow-functions
4. npm i -D @babel/preset-typescript

The React
React will live in Electrons renderer process for that reason we will have to create a separate web pack build configuration. And teach babel to use react loader

1. npm i -D @babel/preset-react
2. npm i -S react react-dom
3. npm i -D @types/react @types/react-dom
