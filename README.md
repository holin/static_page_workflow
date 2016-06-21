# Static Page Workflow

Webpack Workflow for developing static pages.

## Features
1. ES6
2. SCSS
3. Live reload
4. Copy assets files

## Run
```bash
npm install
npm start #run develop server
npm run compile #deploy
```

## Directory tree
```
├── README.md
├── app (work directory)
│   ├── assets
│   │   ├── favicon.ico
│   │   ├── images
│   │   │   └── phoenix.png
│   │   └── robots.txt
│   ├── css
│   │   ├── _base.scss (bootstrap things)
│   │   ├── _variables.scss
│   │   └── app.scss
│   ├── js
│   │   └── app.js
│   ├── pages
│   │   └── index.html
│   └── vendor  
├── package.json
├── public (deploy directory)
│   ├── css
│   │   ├── app.css
│   │   └── app.css.map
│   ├── favicon.ico
│   ├── images
│   │   └── phoenix.png
│   ├── index.html
│   ├── js
│   │   ├── app.js
│   │   └── app.js.map
│   └── robots.txt
└── webpack.config.js
```
