## Deploying a Full-Stack App with Heroku
Hello! This GitHub repo is intended to be used with the article [Deploying a Full-Stack App with Heroku](https://www.codecademy.com/articles/deploying-a-back-end-with-heroku).

Make sure to follow the steps as outlined in the article to see how to use Heroku for your deployment needs!

If you're curious about the app itself feel free to poke around. The server files are located in the root folder. The `/build` folder contains the production code that was created from the front-end folder found in `/client`.

You're free to make changes on your own branch, but for the sake of consistency, we will not be merging any external pull requests. Thank you and happy coding!


## Deploying Using Heroku
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login
Clone the repository
Use Git to clone heroku-codecademy's source code to your local machine.

$ heroku git:clone -a heroku-codecademy 
$ cd heroku-codecademy
Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master
