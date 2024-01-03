## Prerequisites

Node Package Manager are required. Make sure you can `run node --v.`
You can get Node at `nodejs.org`, then install dart-sass using `npm install sass --save-dev`
Bootstrap: `npm install bootstrap`
Dart-Sass/ Sass: `npm install --save-dev sass`
AutoPrefixer: `npm install autoprefixer`

## How to compile the sass files to css

After making sure that you have installed dart-sass which is refered to as sass,
go to the package.json file.
Under scripts remove the test script and add the following script
`"scripts": {

    "compile:sass": "sass --watch scss:assets/css"

}
`

> > > sass --watch scss:assets/css

To compile the sass files just run this

> > > npm run compile:sass

## Getting started

1. Clone this repo
2. Then cd into to the clone project
3. Run npm install
4. Then on your terminal run `npm run compile:sass` to Compile `style.scss` and then make sure you link the `style.css` stylesheet to the head section of the index.html
5. Look at the index.html
6. Add any Bootstrap 5 Sass variables you want to override into `scss/_custom.scss`by copying them from bootstrap `_variables.scss file` check inside `node_modules/bootstrap/scss/_variables.scss`
7. enjoy :-).
