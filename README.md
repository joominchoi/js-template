# Javascript Project Template

Includes:
- Webpack setup
- [ESlint](https://eslint.org/): Most popular and common linter in the industry
- [Prettier](https://github.com/prettier/eslint-config-prettier#installation): Unlike a linter, it’s not looking for style errors, but specifically targeting the layout of your code and making intelligent decisions about things like spaces, indentation levels and line-breaks.
- [Babel](https://github.com/babel/babel-loader): a tool that takes your modern JavaScript code and transpiles it to code that older browsers can understand. It can be used from the command line with a simple command, and can also easily be added to your webpack configuration with the babel-loader.
- Default index.html that contains div within body with the id 'content'
- .gitignore

Use *npx webpack --watch* to run project

Run *npx eslint --init* for setting up and configuring ESLint on a per-project basis - will perform a local installation of ESLint and its plugins in the directory in which it is run

Update as required!