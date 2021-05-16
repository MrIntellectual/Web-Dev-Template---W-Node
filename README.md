# Web Dev Template

This is a template that anyone can use to make a website.

This is made for local development, and you need to have [mongodb community server](https://www.mongodb.com/try/download/community) installed.

Technologies Used: 
* HTML, CSS, JavaScript, TypeScript, and Coffeescript for frontend.
  * Bootstrap 5
  * Font Awesome
  * JQuery
  * Three.js
  * Highlight.js
  * Lodash
  * SCSS
	* React
  * Badges(By @CoolCoderSJ)
* Node.JS for backend.
  * Express
  * EJS
  * Mongoose
  * Lodash
* MongoDB/ReplitDB for Database

To Setup
```shell
git clone https://github.com/MrIntellectual/Web-Dev-Template && cd Web-Dev-Template
npm i
```

To Compile
```shell
# Without JSX
npm run compile
# With JSX
npm run compile-JSX
```

Only do the commands to compile if you want to use SCSS, TypeScript, and CoffeeScript.

If you are using one of them but not the other there are 3 seperate commands
```shell
# For TypeScript
npm run tsc
# For CoffeeScript
npm run coffee
# For Coffeescript with JSX
npm run coffee-JSX
# For SCSS
npm run scss
```

To Start
```shell
npm start
```
or
```shell
node app
```

Note: if you want to change the strict mode on typescript to be false then change the `tsconfig.json` file to have the `strict` property equal to false