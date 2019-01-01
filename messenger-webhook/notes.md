to test the webhook in Glitch
use the link below
https://spiritual-property.glitch.me/webhook?hub.verify_token=%3CYOUR_VERIFY_TOKEN%3E&hub.challenge=CHALLENGE_ACCEPTED&hub.mode=subscribe

to run heroku local web
http://localhost:5000/webhook?hub.verify_token=%3CYOUR_VERIFY_TOKEN%3E&hub.challenge=CHALLENGE_ACCEPTED&hub.mode=subscribe

to run heroku app
https://stormy-caverns-75882.herokuapp.com/webhook?hub.verify_token=%3CYOUR_VERIFY_TOKEN%3E&hub.challenge=CHALLENGE_ACCEPTED&hub.mode=subscribe

-----------
the offical heroku deployment lack the below steps:
git init

git init must be before git add .

link: https://stackoverflow.com/questions/18406721/heroku-does-not-appear-to-be-a-git-repository
