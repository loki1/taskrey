# Taskrey 
## Getting started
Clone the repository into your own folder and update the config/amazon_s3.yml file with your information. (A sample file can be found in config/amazon_s3.yml.sample)

## Deploying (to Heroku)
Change into the directory you cloned Taskrey into. Run
  
    heroku create
    git push heroku master
    heroku rake db:migrate

## First user
Go to your application (on heroku, or wherever you deployed it) and sign up. The first user is setup as the admin user.

## Screenshots
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey.png
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey-1.png
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey-2.png
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey-3.png
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey-4.png
http://bluescripts.s3-website-us-east-1.amazonaws.com/taskrey/Taskrey-5.png
