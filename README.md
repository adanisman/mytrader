
MyTrader is an open source trading platform that displays personalized stock charts showing buy and sell signals according to various algorithms in certain periods in stocks.

MyTrader is a prototype application consisting of 3 separate service layers written with microservice architecture.

MyTraderUI is  UI layer written in REACT
MyTraderAPI is API layer written in JAVA Spring Boot
MyTraderStockSignals is algorithm layer written in Python.

In DB side, PG/SQL is used.
Firebase is used for authentication & authorization.

Whole services deployed to Heroku cloud environment. 

![image](https://user-images.githubusercontent.com/46599537/165378341-c4322a21-c100-458b-a922-30c177b2d334.png)


![image](https://user-images.githubusercontent.com/46599537/165374567-4a46b478-f5a6-4614-9e23-180366fa5c70.png)

![image](https://user-images.githubusercontent.com/46599537/165374422-44442328-b357-45d8-948a-4972c6fec509.png)



## Versions



### Instalation

``` bash
$ npm install
```

or

``` bash
$ yarn install
```

### Basic usage

``` bash
# dev server with hot reload at http://localhost:3000
$ npm start 

# if you use Node 17+ use this command instead of `npm start`
$ npm run start:n17 
```

or 

``` bash
# dev server with hot reload at http://localhost:3000
$ yarn start

# if you use Node 17+ use this command instead of `yarn start`
$ yarn start:n17 
```

Navigate to [http://localhost:3000](http://localhost:3000). The app will automatically reload if you change any of the source files.

#### Build

Run `build` to build the project. The build artifacts will be stored in the `build/` directory.

```bash
# build for production with minification
$ npm run build

# if you use Node 17+ use this command instead of `build run build`
$ npm run build:n17 
```

or

```bash
# build for production with minification
$ yarn build

# if you use Node 17+ use this command instead of `yarn build`
$ yarn build:n17 
```

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
coreui-free-react-admin-template
├── public/          # static files
│   └── index.html   # html template
│
├── src/             # project root
│   ├── assets/      # images, icons, etc.
│   ├── components/  # common components - header, footer, sidebar, etc.
│   ├── layouts/     # layout containers
│   ├── scss/        # scss styles
│   ├── views/       # application views
│   ├── _nav.js      # sidebar navigation config
│   ├── App.js
│   ├── ...
│   ├── index.js
│   ├── routes.js    # routes config
│   └── store.js     # template state example 
│
└── package.json
```

## Documentation


## Versioning


