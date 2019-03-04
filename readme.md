# Gulp Template

## How to use

1.  To use svg: create in pug +icon('name of svg'). In css adding class i plus i-name
2.  Install babel:
    > npm install --save-dev gulp-babel @babel/core @babel/preset-env
3.  Install eslint:
    > npm install eslint --save-dev
    > create .eslintrc and add {"extends": ["airbnb"]} (I use airbnb)
    > npx install-peerdeps --dev eslint-config-airbnb
4.  Add prettier:
    > npm install --save-dev prettier
    > create .prettierrc and add rules {
          "printWidth": 80,
          "singleQuote": true,
          "semi": true,
          "bracketSpacing": true
    }
    > npm install --save-dev eslint-config-prettier (to config js)
    > add scripts to package.json "scripts":
    > "lint": "eslint '**/\*.{js,jsx}' --quiet",
    > "format": "prettier --write '**/\*.{js,jsx}'"

### Inc

1. Pug
2. Scss
3. SVG module
4. PNG module
5. Babel
6. Eslint
7. Prettier
8. Bootstrap
9. Fontawesome

#### Structure

source > css > favicon > font > img > js > module > svg > template
gulp > config > tasks

#### Run (develop)

npm i
gulp

#### Build (build min)

gulp build
