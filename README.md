# create-react-app-mulipage
> A simple multiple pages project for react, rewrite create-react-app, based on npm ran eject of CRA


## core react dependencies
```
"dependencies": {
  "react": "^16.6.3",
  "react-dom": "^16.6.3",
  "react-scripts": "2.1.1"
},
```
> react-scripts@version >= 2.1.2, webpack config only has webpack.config.js, but current project use react-scripts@2.1.1 with webpack.config.dev.js and webpack.config.prod.js as webpack config


## coding example
```
|-- src
    |-- yourfolder // name of html would be the same as your folder name
        |-- App.css
        |-- App.js
        |-- index.css
        |-- index.js
        |-- logo.svg
```


## install dependencies
```
yarn install (or npm install)
```

## run the project
```
npm start
http://localhost:3000/dashboard.html
http://localhost:3000/mine.html
```


## build the project
```
npm run build
```



<br />
Thanks for:<br/>
[React CRA multiple pages](https://segmentfault.com/a/1190000016960824)<br />
[Webpack for Create React App](https://zhaozhiming.github.io/blog/2018/01/08/create-react-app-override-webpack-config/)
