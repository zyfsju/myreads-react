# myreads-react

![](myreads-react-demo.gif)
I developed this app for [React Nanodegree on Udacity](https://github.com/udacity/reactnd-project-myreads-starter). I used [Create React App](https://github.com/facebookincubator/create-react-app) to bootstrap the project. 

* install all project dependencies with `npm install`
* start the development server with `npm start`

## Folder Structure
```bash
├── README.md - This file.
├── SEARCH_TERMS.md # The whitelisted short collection of available search terms for the app to work.
├── package.json
├── public
│   ├── favicon.ico
│   └── index.html
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── BooksAPI.js # A JavaScript API for the provided Udacity backend.
    ├── icons
    │   ├── add.svg
    │   ├── arrow-back.svg
    │   └── arrow-drop-down.svg
    ├── index.css
    └── index.js
```

## Backend Server

The backend server is provided by Udacity. The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](SEARCH_TERMS.md). That list of terms are the _only_ terms that will work with the backend.
