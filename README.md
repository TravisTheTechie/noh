noh
===

Example simple Node on Heroku

1. Install [Heroku Toolbelt](https://toolbelt.herokuapp.com/)
2. `$ heroku login`
3. `$ heroku keys:add` to add your ssh key
4. `$ npm install`
5. `$ foreman start` to run locally (foreman from Heroku Toolbelt)
6. `$ heroku create`
7. `$ git push heroku master`
8. `$ heroku ps:scale web=1`
9. Check to see what's going on at Heroku
  `$ heroku ps`
