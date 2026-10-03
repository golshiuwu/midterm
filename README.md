
npm audit fix --force
ExpressHandlebars is not a function. change cont expressHandlebars = require('erxpress-handlebars')
to const { engine } = require('express-handlebars')
according to https://www.npmjs.com/package/express-handlebars