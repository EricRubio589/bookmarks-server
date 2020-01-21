# Bookmarks app server!

This is a server that works in conjuction with the bookmarks app.

## Set up

Make sure this is runnig before running the bookmarks app.

## Important!

This server utilizes an API Bearer token, make sure to generate an API_TOKEN in the .env file 

## Deploying

When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new git remote called "heroku" and you can then `npm run deploy` which will push to this remote's master branch.
