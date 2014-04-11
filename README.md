# yeoman-fullstack

a quickstart guide to get a Nodejs production-ready site up and running

Getting your app from a playground state to a production ready application is usually a project in itself. 
So why not just cut out that part and start with a production ready set-up. 

***Enter Yeoman***. It's a generator like any other but scaffolds up your website and packages it ready-to-deploy.


## View Live Demo

[http://yeoman-fullstack.herokuapp.com/](http://yeoman-fullstack.herokuapp.com/)

## Create your own from scratch

``` bash
# install dependencies
npm install -g yo
npm install generator-angular-fullstack

# scaffold out a AngularJS project with Express
yo
# From the menu choose
generator-angular-fullstack
# run tests
grunt test
# run in development server
grunt serve
# build application for deployment
grunt

```

## Deploy to Heroku

``` bash
yo angular-fullstack:deploy heroku
cd dist && git push heroku master
heroku ps:scale web=1
heroku open
```

## Trouble Shooting