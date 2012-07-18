noh
===

Example simple Node on Heroku

1. Install [Heroku Toolbelt](https://toolbelt.herokuapp.com/)
2. `$ heroku login`
3. `$ npm install`
4. `$ foreman start` to run locally (foreman from Heroku Toolbelt)
5. `$ heroku create`
6. `$ git push heroku master`
7. `$ heroku ps:scale web=1`
8. Check to see what's going on at Heroku
  `$ heroku ps`
