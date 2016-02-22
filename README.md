# Lightning Experience Demo 
This is a demo application for Lightning Experience sandbox practicing.

The application was created following the steps described in [this link](https://www.lightningdesignsystem.com/getting-started/heroku)


## Steps for replicating this demo from scratch
mkdir lightning-demo
cd lightning-demo
npm init  #set the init file to server.js
npm install express --save
npm install @salesforce-ux/design-system
mkdir public
touch public/index.html
touch server.js
touch Procfile
...
heroku create heroku-lightning-demo
$ git add .
$ git commit -m "Init"
$ git push origin master
$ git push heroku master

